# 📝 Interview Management System

Interview Management System is a web app built using the Frappe Framework.
It helps manage interviews easily — like adding candidates, scheduling interviews, and tracking their status.

##📁 Management
This app is made for handling interviews. It helps teams to:
- Add and manage candidate details
- Schedule interviews with date and time
- Track interview status (like Scheduled, Selected, Rejected)
- Keep records of interview results
- (Optional) Send reminders and updates

# ⚙️ Installation
You can install this app using the [bench ](https://github.com/frappe/bench)CLI:

<pre>cd $PATH_TO_YOUR_BENCH
bench get-app $URL_OF_THIS_REPO --branch main
bench install-app management</pre>

# 🤝 Contributing
This app uses pre-commit for code formatting and linting. Please [install pre-commit](https://pre-commit.com/#installation) and enable it for this repository:

Go to the app folder:

<pre>
cd apps/management
pre-commit install</pre>

# 🧹 Tools used with pre-commit
- 🐍 ruff – Checks Python code
- 🌐 eslint – Checks JavaScript code
- 🎨 prettier – Formats the code to look clean
- 🆙 pyupgrade – Updates old Python code to new style

