<properties linkid="" urlDisplayName="" pageTitle="" metaKeywords="" description="" metaCanonical="" services="" documentationCenter="" title="What is Windows Azure Multi-Factor Authentication?" authors=""  solutions="" writer="billmath" manager="terrylan" editor="lisatoft"  />





<h1 id="whatiswamfa">What is Windows Azure Multi-Factor Authentication?</h1>

Multi-factor or two-factor authentication is a method of authentication that requires the use of more than one verification method and adds a critical second layer of security to user sign-ins and transactions. It works by requiring any two or more of the following verification methods: 

* Something you know (typically a password)
* Something you have (a trusted device that is not easily duplicated, like a phone)
* Something you are (biometrics)

The security of multi-factor authentication lies in its layered approach. Compromising multiple authentication factors presents a significant challenge for attackers. Even if an attacker manages to learn the user's password, it is useless without also having possession of the trusted device. Conversely, if the user happens to lose the device, the finder of that device won't be able to use it unless he or she also knows the user's password.
Windows Azure Multi-Factor Authentication is the multi-factor authentication service that requires users to also verify sign-ins using a mobile app, phone call or text message. It is available to use with Windows Azure Active Directory, to secure on-premise resources with the Windows Azure Multi-Factor Authentication Server, and with custom applications and directories using the SDK. 

![Windows Azure Multi-Factor Authentication](./media/multi-factor-authentication/WAMFA1.png)

<h3>Securing cloud Windows Azure Active Directory</h3>

Enable Multi-Factor Authentication for Windows Azure AD identities, and users will be prompted to set up additional verification the next time they sign in. Use Multi-Factor Authentication to secure access to Windows Azure, Microsoft Online Services like Office 365 and Dynamics CRM Online, as well as 3rd party cloud services that integrate Windows Azure AD with no additional set up. Multi-factor authentication can be rapidly enabled for large numbers of global users and applications.  [Learn more](http://msdn.microsoft.com/en-us/library/dn249466.aspx)

<h3>Securing on-premises resources and Active Directory</h3>

Enable Multi-Factor Authentication for your on-premise resources such as IIS and Active Directory using the Windows Azure Multi-Factor Authentication Server.  The Windows Azure Multi-Factor Authentication Server allows the administrator integrate with IIS authentication to secure Microsoft IIS web applications, RADIUS authentication, LDAP authentication, and Windows authentication.  [Learn more](http://msdn.microsoft.com/en-us/library/dn249467.aspx)
<h3>Securing custom applications</h3>

An SDK enables direct integration with your cloud services. Build Active Authentication phone call and text message verification into your application's sign-in or transaction processes and leverage your application's existing user database. [Learn more](http://msdn.microsoft.com/en-us/library/dn249464.aspx)

<h3>Multi-Factor Authentication for Office 365</h3>

Multi-Factor Authentication for Office 365, powered by Windows Azure Multi-Factor Authentication, works exclusively with Office 365 applications and is managed from the Office 365 portal. So administrators can now secure their Office 365 resources with multi-factor authentication. [Learn more](http://msdn.microsoft.com/en-us/library/dn383636.aspx)

<h3>Multi-Factor Authentication for Windows Azure Administrators<h3>

The same subset of Multi-Factor Authentication capabilities for Office 365 will be available at no cost to all Windows Azure administrators. Every administrative account of a Windows Azure subscription can now get additional protection by enabling this core multi-factor authentication functionality. So an administrator that wants to access Windows Azure portal to create a VM, a web site, manage storage, mobile services or any other Windows Azure Service can add multi-factor authentication to his administrator account.  [Learn more](http://msdn.microsoft.com/en-us/library/dn249471.aspx)

<h3>Multi-Factor Authentication feature comparison</h3>

The following shows the versions of multi-factor authentication that are available and a brief summary of the features it provides. You can use this in determining which version of multi-factor authentication is right for you. [Learn more](http://msdn.microsoft.com/en-us/library/dn249471.aspx)

![Windows Azure Multi-Factor Authentication Feature Comparison](./media/multi-factor-authentication/mfacomparison1.png)


**Additional Resources**

* [Sign up for Windows Azure as an organization](/en-us/manage/services/identity/organizational-account/)
* [Windows Azure Identity](/en-us/manage/windows/fundamentals/identity/)
* [Windows Azure Multi-Factor Authentication Library](http://technet.microsoft.com/en-us/library/dn249471.aspx)

