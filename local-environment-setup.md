30JAN17:
1.	Have personal github account: 
	a.	Went to github.com on mozzilla firefox on windows 7.
	b.	Established a username, password and provided an email address (unh student email).
	c.	Once the profile is established, GitHub sends a confirmation email to the email address provided. 
	d.	In that email, click on the “Verify email address” link.
	e.	Informed the professor of the username for the account.
	f.	Professor sent invitation to join unh-comp-698-systems-software github organization.
	g.	Accepted invitation to join unh-comp-698-systems-software github organization.
2.	Established that there is a “bash” terminal running locally on my computer already.
3.	Established that Git Client already exists on my computer.
4.	Obtaining docker from docker.com
	a.	Attempted to download docker for windows.
	b.	Downloaded successfully but the installation errored out as the installer was looking for the docker toolbox.
	c.	Went back to docker.com to download docker toolbox
	d.	Downloaded docker toolbox successfully.
	e.	Attempted installation.
	f.  Installation failed due to docker looking for x86/64 processor and seeing an i686 processor.
	g.  Per research on the Internet, enabling Virtual Machines in the computer's BIOS should solve the problem.
	h.  Closed all applications and rebooted computer. 
	i.  Pressed "escape" key during boot process to enter BIOS.
	j.  Changed Virtualization from Disabled to Enabled and saved the change. 
	k.  Continued boot process.
	l.  After logging in, started docker successfully.
5.  Received error when trying to enter the following: "docker run -it ubuntu:xenial/bin/bash" which gave the following error:
	"docker: Error parsing reference: "ubuntu:xenial/bin/bash" is not a valid repository/tag: invalid reference format."
	Notified Professor Couture of this error and awaiting reply.
	a. Informed of syntax error by Professor where there should be a space between "xenial" and "/bin/bash". 
	b. Brought up Oracle VM VirtualBox again, ran ubuntu(64 bit) again, entered "docker run -it ubuntu:xenial /bin/bash" and
	a newer image for ubuntu:xenial was downloaded then the following appeared "root@ad25914c926b:/#" as the prompt. 
