# Permissions
How to change permissions using Filezilla
File Permissions
Linux
<p>Each file has their own permission</p>
<p>“-“ = files</p> 
<p>“d” = directories</p>
<p> r = Read</p>
<p> w = Write</p>
<p> x = Execute</p>

<p>3 Groups (Owner, Group, Other)</p>

<p>Octal Number = i.e. 755
First number = User
Second number = Group
Third Number = Other(Outside World)</p>

<p>What do these numbers mean?</p>
<p>4 = read</p>
<p>2 = write</p>
<p>1 = execute</p>
<p>0 = no permission</p>
<p>7 = combination of numbers: read, write, execute permission</p>
<p>5 = combination of numbers read, execute</p>
<p>777 = Has all permissions(Let anyone do what they want)</p>
<p>Typical method: 755 for directories, 644 for files, html, images</p>

https://www.youtube.com/watch?v=UXBNQMzvSRQ
Can quickly change permission of directories and files using Filezilla
Highlight folders you want to change permissions to
Right click
Choose “Change Permissions”
Change to 755
Click recurser 
Choose apply to all subdirectories
Click save
Highlight files you want to change permissions to
Right click
Choose “Change Permissions”
Change to 755
Click Recurser
Choose apply to all files
FileZilla will take a bit but will be done fast




