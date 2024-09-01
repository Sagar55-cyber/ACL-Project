# ACL-Project
In our company's IT infrastructure, we have three distinct servers: a login server, a website server, and an FTP server. To enhance security and ensure proper access control, the company's administrator has mandated that employees should not have direct access to the FTP server.

To achieve this, I configured access control lists (ACLs) on the company router. These ACLs are designed to block access from employee devices to the FTP server, effectively preventing any interaction with it. Instead, employees are allowed to use the login server for authentication purposes and the website server for accessing web content.

This configuration ensures that while employees can still log in and use the company's website for their tasks, they cannot connect to or manipulate files on the FTP server, thus maintaining a higher level of security and control over our network resources.
