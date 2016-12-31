# AdobeDigitalSignatureService
This service adds a signature line and digitally signs your document of choice programatically. If you have a need for authentication of documents via signature algorithms this service will help you do that. 

The addSignatureLine class invokes Adobe Livecycle to add a signature field in your document of choice. 
The signDigitalSignature class then creates a digital signature on the signature field using the credential object and HashAlgorithm.SHA1. 

Your hardware security module will serve as the credential object for the digital signature. 


