# SW302
SW302-Project
Repo: https://github.com/Kh4led-05/SW302.git

SETUP (once)
1. git clone https://github.com/Kh4led-05/SW302.git
2. cd ProjectSW302/frontend
3. npm install
   (if it says scripts are disabled, run:
    Set-ExecutionPolicy -Scope CurrentUser RemoteSigned)
4. Install the "Tailwind CSS IntelliSense" extension in VS Code
5. git checkout -b yourname    (ali, kareem, or saif)

OUR PAGES (all in frontend/pages/, one responsive file each)
Ali:    home.html, dashboard.html
Kareem: exercises.html, exercise-detail.html
Saif:   routine-form.html, settings.html
Khaled: profile.html, login.html, register.html

FOR EACH PAGE
1. Copy frontend/components/page-template.html into frontend/pages/ and rename it
2. Change "Page Name" in the <title> and <h1>
3. Build inside <main> only. Do NOT edit the navbar or footer
4. npm run build (inside frontend), then open the file in the browser
5. Check mobile and desktop widths
6. git add . / git commit -m "clear message" / git push -u origin yourname
7. When a page is ready, open a Pull Request into main