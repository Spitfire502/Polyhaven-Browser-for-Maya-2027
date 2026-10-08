# Polyhaven-Browser-for-Maya-2027
Import HDRIs, materials and models into Maya 2027


Poly Haven Browser by Chris Hughes
====================================

Requires: Maya 2027


INSTALLATION
------------
1. Copy the "poly_haven_browser" folder to:
   {PathToDocuments}\Documents\maya\2027\scripts\

   Example of the final folder structure:
   Documents\maya\2027\scripts\poly_haven_browser\__init__.py
   Documents\maya\2027\scripts\poly_haven_browser\core.pyc
   Documents\maya\2027\scripts\poly_haven_browser\icons\polyhaven_icon.png
   Documents\maya\2027\scripts\poly_haven_browser\README.txt

2. Run Maya 2027.

3. In the Script Editor's "Python" tab, run this command once (all on one
   line - Maya's single-line command entry doesn't handle two separate
   lines pasted together, so the semicolon matters here):

   import poly_haven_browser as ph_browser;ph_browser.Init()

4. Look for the "PolyHaven" tab on your Shelf. Click the button (Poly
   Haven logo icon) any time to launch the tool - you only need to run
   Init() once, ever (it saves the shelf button permanently).

<img width="756" height="412" alt="Screenshot 2026-10-07 193243" src="https://github.com/user-attachments/assets/96366283-5274-44b4-bb61-5545d8148d8d" />

USAGE
-----
- Pick a destination folder using the folder icon.
- Use the HDRIs / Materials / Models buttons to search and download from
  Poly Haven, browse by category, sort by newest, and refresh for new
  releases.
- Use the Load button to browse what you've already downloaded locally.
- Click a downloaded HDRI to assign it to your scene's SkyDome light
  (works with multi-resolution downloads too - you'll get a picker).
- Right-click any downloaded item to delete it.
<img width="892" height="678" alt="Screenshot 2026-10-07 193227" src="https://github.com/user-attachments/assets/1409dd20-27bf-48ff-b723-a218e990279c" />
<img width="897" height="681" alt="Screenshot 2026-10-07 193257" src="https://github.com/user-attachments/assets/28c171d0-37a4-4807-af7c-1be20cdb5aea" />
<img width="893" height="862" alt="Screenshot 2026-10-07 193330" src="https://github.com/user-attachments/assets/01670ff0-714f-4b90-a5b4-442c6d5f9580" />


COMPATIBILITY
-------------
This tool is built specifically for Maya 2027. It will not
run on other Maya versions - Autodesk changes Python's internal bytecode
format between major versions, and this package ships pre-compiled for
Maya 2027 only. If you're on a different Maya version, contact the author
for a compatible build.

https://vimeo.com/user255443974/phbrowser?share=copy&fl=sv&fe=ci
