## HTTP Info

> HTTP basic authentication:

> The username and password should be transmitted in the format of a String such as "username:password"

> The string should be base64 encoded, not for security, but to encode non-HTTP-compatible characters into HTTP-compatible characters that may be in the username or password.

> Encoded authorization string format:
 Authorization: Basic [insert base64 encoded string here]`
