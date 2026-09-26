# GEVIP website 

This is an updated website for Galaxy Evolution VIP at UT Austin. 

**The website is still a work in progress. Please try it out and share your feedback!** 

## Download and open the website

### Option 1: Download ZIP — easiest

1. Open https://github.com/yuni1218/gevip-website.
2. Click the green **Code** button, then **Download ZIP**.
3. Extract the downloaded ZIP:
   - **Mac:** double-click the ZIP file.
   - **Windows:** right-click it and select **Extract All**.
4. Open the extracted folder.
5. Double-click `index.html` to open the website in your browser. You can also right-click it and choose **Open With → Chrome, Firefox, Safari, or Edge**.

If the HTML file is still named `gevip_cosmic_atlas_v3.html`, open that file instead.

**Keep the HTML file and the `images` folder together.** Opening the HTML while it is still inside the ZIP, or moving it away from the images, may prevent photos from loading.

### Option 2: Clone with Git

If you have Git installed, open Terminal or PowerShell and run:

```bash
git clone https://github.com/yuni1218/gevip-website.git
cd gevip-website
```

Then open `index.html` from that folder in your browser.

To download later updates, run this command inside the repository folder:

```bash
git pull
```

If you used the ZIP option, download and extract a fresh ZIP to get the latest version.

### If photos don’t appear: run a local preview

If Python is installed, open Terminal or PowerShell and navigate to the website folder:

```bash
cd "/path/to/gevip-website"
```

Replace `/path/to/gevip-website` with the location of your downloaded or cloned folder.

**Mac / Linux:**

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

**Windows:**

```powershell
py -m http.server 8000 --bind 127.0.0.1
```

Leave the terminal running and open http://localhost:8000 in your browser.

Press **Control+C** in the terminal to stop the preview when finished.
