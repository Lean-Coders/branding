# List of AD attributes avail in signature via %%macro

Used in mail flow rules	Used in a VBScript
General	
%%DisplayName%%	AD DS: displayName
%%FirstName%%	AD DS: givenName
%%Initials%%	AD DS: initials
%%LastName%%	AD DS: sn
%%Office%%	AD DS: physicalDeliveryOfficeName
%%PhoneNumber%%	AD DS: telephoneNumber
%%OtherPhoneNumber%%	AD DS: otherTelephone
%%Email%%	AD DS: mail
Address	
%%Street%%	AD DS: streetAddress
%%POBox%%	AD DS: postOfficeBox
%%City%%	AD DS: l (as in "location")
%%State%%	AD DS: st
%%ZipCode%%	AD DS: postalCode
%%Country%%	AD DS: co
Account	
%%UserLogonName%%	AD DS: userPrincipalName
Telephones	
%%HomePhoneNumber%%	AD DS: homePhone
%%OtherHomePhoneNumber%%	AD DS: otherHomePhone
%%PagerNumber%%	AD DS: pager
%%MobileNumber%%	AD DS: mobile
%%FaxNumber%%	AD DS: facsimileTelephoneNumber
%%OtherFaxNumber%%	AD DS: otherFacsimileTelephoneNumber
%%Notes%%	AD DS: info
Organization	
%%Title%%	AD DS: title
%%Department%%	AD DS: department
%%Company%%	AD DS: company
%%Manager%%	Returns the common name (cn) of the object defined
in the manager AD DS attribute

https://www.mail-signatures.com/articles/active-directory-data-in-email-signatures/