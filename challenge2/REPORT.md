## Challenge 2

### Difference Between Reflected and Stored XSS

Reflected XSS occurs when malicious input is immediately returned in an HTTP response and executed by the victim's browser. Stored XSS occurs when malicious input is permanently stored by the application and later delivered to users who visit the page. This challenge demonstrates Stored XSS because comments are saved and displayed whenever the page is loaded. Stored XSS is generally more dangerous because every visitor to the affected page can become a victim. Attackers can use it to steal sessions, impersonate users, or modify page content.