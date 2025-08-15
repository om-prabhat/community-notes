# 🗒️ Community Pentest & CTF Notes

A community-driven collection of pentesting and CTF notes, cheatsheets, and examples.  
Perfect for exam prep, CTFs, or just general security reference.

## 📝 How to Contribute

1. **Use variables** - Replace hardcoded values with placeholders:
   - `<target>` for IPs/domains
   - `<username>`/`<password>` for credentials
   - `<hash>` for hash examples (use "password" as base if needed)

2. **Keep it clean**:
   ```bash
   # Good
   nmap -sV <target>
   
   # Bad
   nmap -sV 192.168.1.100


3. An example note for md5
  ```
  # Show hash formats
  echo -n "password" | md5sum
  # => 5f4dcc3b5aa765d61d8327deb882cf99
```

Images not required as when users search notes - they will be looking for words. Explain clearly. 

Remember: Your contributions in turn encourage others to contribute. This leads to an ecosystem where we all benefit from the provided notes.
