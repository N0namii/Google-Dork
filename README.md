**Google Dork Automation Tool**  
A Python script for automating Google Dorking searches. This tool allows you to perform advanced searches using various dorks to find specific information on the web. It supports multiple dorks like `site:`, `inurl:`, `intitle:`, and more, making it a powerful tool for security researchers, penetration testers, and anyone interested in exploring publicly available data.

---

### **Key Features**  
- **Supports multiple dorks**: Search using `site:`, `inurl:`, `intitle:`, `filetype:`, and other operators.  
- **Flexible**: Allows you to specify the number of results for each query.  
- **Easy to use**: Run the script via the command line with minimal parameters.  

---

### **How to Use**  
1. Install the required library:
   ```bash
   pip install googlesearch-python
   ```
2. Run the script:
   ```bash
   python go_dork.py example.com
   ```
3. Use the `--num_results` flag to specify the number of results:
   ```bash
   python go_dork.py example.com --num_results 5
   ```

---

### **Example Dorks**  
- `site:example.com` — Search within a specific site.  
- `inurl:admin` — Search for URLs containing the word "admin".  
- `filetype:pdf` — Search for specific file types (e.g., PDF).  
- `intitle:"index of"` — Search for open directories.  

---

### **License**  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

