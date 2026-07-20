LOCAL TESTING

Recommended:
1. Extract the complete package.
2. Open the extracted v2fitness-website-complete folder.
3. Double-click START-LOCAL-TEST.bat.
4. Keep the command window open while testing.
5. Visit:
   http://localhost:8000/
   http://localhost:8000/youth-os/
   http://localhost:8000/youth-os/growth-maturation/
   http://localhost:8000/privacy/
   http://localhost:8000/terms/

If 'python' is not recognised, install Python and tick 'Add Python to PATH',
or run: py -m http.server 8000

Netlify redirects such as /height are not applied by Python's simple server.
Test those after deployment or with Netlify CLI.
