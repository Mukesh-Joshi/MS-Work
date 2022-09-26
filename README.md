HtmlSanitizer
=============

The complete code is a replica of the code written by Rich Strahl on HTML sanitization at
https://github.com/RickStrahl/HtmlSanitizer.git 

The existing code used a denylist approach to blocking potentially malicious input HTML text posted.
I have changed the code with following:
1. Allowlist based approach, i.e., the only allowed HTML tags will be passed.
2. The Allowlist can be configured in the .config file, or can be passed to an overloaded method. Each node shoudl be separated with a pipe sign (|)
