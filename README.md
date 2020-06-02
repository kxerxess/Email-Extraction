# Email-Extraction
 Pyhton based email extractor to extract emails based on chosen keywords

I used the imaplib and email modules of python to establish a connection and login to the mail with the provided user details. Then I iterated over all mails present in the 'Inbox' section of the user. I extracted the subject, details of sender and contents of the mail. I checked if the subject or mail content include the words given in the checkWords list. (Congrat and congrat by default) If the words were found, the subject of this mail was returned. As soon as 5 mails sujects were returned the loop was exited and the subjects of these mails were displayed.
