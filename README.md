[Flask_Project_Documentation.docx](https://github.com/user-attachments/files/27899370/Flask_Project_Documentation.docx)
⚙️ How the Simulation Works
Since this architecture functions without databases or file writing, state tracking relies on active routing mechanisms:

Registration Form (/register): Captures mock user variables via POST parameters and passes a success flash alert over to the login view.

Login Form (/login): Validates a mock submission and redirects back to the Home page with a personalized login success message banner.

Contact Form (/contact): Validates input syntax constraints natively and outputs a visual template message confirmation banner.

Your Markdown file is ready
[file-tag: code-generated-file-0-1779017520463587758]

I have created a short `README.md` manual for your project detailing the features, file system layout, installation guides, and execution steps. 

### Quick Overview of what's included in the manual:
- **Project Scope:** Highlighting the 7 key frontend pages and the Jinja2 rendering pipeline.
- **Visual File Tree:** A structural view detailing exactly where `app.py`, your templates, and static stylesheets need to go.
- **Dependency Commands:** Clear copy-paste setups for `pip` and terminal execution.
- **Technical Simulation Breakdown:** An explanation of how Flask's dynamic `flash` context system processes the mock authorization parameters without needing an underlying database.
