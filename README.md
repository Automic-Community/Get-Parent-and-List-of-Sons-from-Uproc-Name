*Get Parent and List of Sons from Uproc Name*
=============


Return the list of Children and the Name of the Father (if any) in a simple format.
http://github.com/Automic-Community/Get-Parent-and-List-of-Sons-from-Uproc-Name

<!-- List of attached files -->
Contents of Solution Package:

						
								*Get_Info_uproc_in_Session.zip
								
						


Documenation and Instructions
---

<p><span><strong class="bbc">Description:</strong></span><br /><br />Given the name of an existing Session as the first Parameter, and the name of a Uproc within the Session as a second parameter, this tool will return the list of Children and the Name of the Father (if any) in a simple format.<br /><br /><span><strong class="bbc">How to use it:</strong></span><br /><br />Two Parameters need to be passed to the script:<br /><br />1- Session Name (Must Exist)<br />2- Uproc Name (Must Exist and belong to Session)<br /><br />ex:<br />./getInfoUprocInSession.sh "MY SESSION" "MY UPROC"<br /><br />Meaning of Output:<br /><br />A --&gt; B: A is father of B<br />B &lt;-- C: B is son of C<br />D &lt;-- : D has no father (and therefore is the Header)<br />E --&gt; : E has no son</p>
<p>&nbsp;</p>
<p><strong class="title">Target environments:</strong> Linux, Unix</p>
<p><strong class="title">Prerequisites:</strong> DU6 (could be adapted to DU5), local machine (could be adapted to work on remote machines as well)</p>
<p><strong class="title">Implementation:</strong></p>
<ul style="list-style-type: undefined;">
<li>Load the environment variables</li>
<li>Run the script</li>
</ul>

Copyright and License
---

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
