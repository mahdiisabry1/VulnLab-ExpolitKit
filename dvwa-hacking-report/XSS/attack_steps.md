# XSS Attack Steps

# XSS Attack Steps - DVWA

## Target: DVWA - Cross Site Scripting (XSS)

### XSS Types Covered:
- Reflected XSS
- Stored XSS
- DOM-Based XSS

---

## 🔹 1. Reflected XSS

### Low Security:
1. Navigate to `Vulnerabilities -> XSS (Reflected)`.
2. In the **Name** field, enter:
   ```html
   <script>alert('XSS')</script>
