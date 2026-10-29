SW302

SW302-Project Repo: https://github.com/Kh4led-05/SW302.git

https://www.figma.com/design/hJlWjAXxfLAffLfpw9H7e6/Navbar-Footer?node-id=11-39&t=RufqtW1vG0NJqRBV-1

SETUP (once)

git clone https://github.com/Kh4led-05/SW302.git
cd SW302/frontend
npm install (if it says scripts are disabled, run: Set-ExecutionPolicy -Scope CurrentUser RemoteSigned)
Install the "Tailwind CSS IntelliSense" extension in VS Code
git checkout -b yourname (ali, kareem, or saif)

OUR PAGES (all in frontend/pages/, one responsive file each) Ali: home.html, dashboard.html Kareem: exercises.html, exercise-detail.html Saif: routine-form.html, settings.html Khaled: profile.html, login.html, register.html

FOR EACH PAGE

Copy frontend/components/page-template.html into frontend/pages/ and rename it
Change "Page Name" in the <title> and <h1>
Build inside <main> only. Do NOT edit the navbar or footer
npm run build (inside frontend), then open the file in the browser
Check mobile and desktop widths
git add . / git commit -m "clear message" / git push -u origin yourname
When a page is ready, open a Pull Request into main
