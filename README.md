Download Link: https://assignmentchef.com/product/solved-605-681-module-2-homework-for-html
<br>
Create a simple WWW page accessible at your home directory on the class computer (see <u>Class Resources</u>). For those of you with web experience, yes, you may use CSS rather than the tags covered in this chapter. But for those of you just starting out, the simple tags are probably easiest for this first assignment.

The fictional Beartooth Hiking Company (BHC) is thinking about making a simple web page that shows some of their services and a few photos. You’ll get to love the BHC, as they provide oh so many homework opportunites in weeks to come!

They’d like you, the expert HTML designer, to come up with something. The web page should use HTML and include <strong><em>all</em></strong> of the following:

A link to another document, in this case the wilderness.net website with more information on the area. The URL is http://www.wilderness.net/index.cfm?fuse=NWPS&amp;sec=wildView&amp;WID=1 At least one embedded image. Some images are found at the bottom of this page, you can save the images and then use them in your web page.

A list. The list should show three hiking tours. It should include Gardiner Lake, the Hellroaring Plateau, and The Beaten Path.

A table showing tour options to the above destinations shown in the list. The Gardiner Lake tour is 3 or 5 days, and is intermediate, the cost is $40/day. The Hellroaring Plateau is 2, 3, or 4 days and is $35/day and is an easy hike. The Beaten Path trip is 5 or 7 days and is $45/day and is a difficult hike. All hikes have a 50% surcharge for Sat/Sun hikes.

<strong>Submission:</strong>

Upload the files to the Tomcat web server on the <strong>web6.jhuep.com</strong>. Include in your blackboard submission comments the URL to your web page.

Once you have the HTML files created, you need to upload them to the course computer. (<em>the sftp/scp/pscp option below is probably easiest</em>).

To use SFTP (FTP is a bad thing) the files to the public_html directory on you account on the class computer. Remember, SFTP/SCP use port 22 to connect! If you haven’t used sftp before, you would do something like:

<ol>

 <li>sftp &lt;your JHU username&gt;@&lt;the class computer&gt;</li>

 <li>&lt;enter your password&gt;</li>

 <li>if you started the sftp process other than in the directory that contains the files, use the “lcd” command to change “local” directory to where the files are located</li>

 <li>use the “put” command to now upload the files</li>

</ol>

To use SCP,

Open a shell window and then cd to the directory that contains the files, then

<ol>

 <li>scp <em>SourceFile.ext &lt;your JHU username&gt;</em>@<em>&lt;the course computer&gt;</em>:<em>public_html</em>/<em>TargetFile.ext</em></li>

</ol>

To use Putty SCP (pscp.exe)

<ol>

 <li>pscp <em>SourceFile.ext &lt;your JHU username&gt;</em>@<em>&lt;the course computer&gt;</em>:<em>public_html</em>/<em>TargetFile.ext </em>Your final step is to include the URL to your homework in your blackboard comments.</li>

</ol>

You can also use FileZilla, which is a GUI based file transfer application.

<strong>File Permissions</strong>

One issue that students have had problems with before is file permissions on the Unix host.

When you upload, you can see file permissions on files in a directory by typing

ls -la

All of your directories should be at least drwxr-xr-x, your files should be -rw-r–r–.

If they aren’t you can change directory permissions with

chmod 755 &lt;directory name&gt;

And you can change file permissions with

chmod 644 &lt;file names&gt;

You can use wildcards as part of the file/directory names.

<strong>Images</strong>

<ul>

 <li>of 2 9/1/18, 1:20 PM Homework</li>

</ul>