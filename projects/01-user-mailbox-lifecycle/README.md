
### 🖼️ Step 3: Add Your Screenshots

For the images to show up, you need to create a `screenshots` folder inside `01-user-mailbox-lifecycle`.

1.  Go back to your repository main page.
2.  Navigate into `projects` → `01-user-mailbox-lifecycle`.
3.  Click **"Add file"** → **"Upload files"**.
4.  Drag and drop your 3 redacted screenshots.
5.  **Important:** Rename your files before uploading (or after) to match exactly:
    - `01-add-user.png`
    - `02-assign-license.png`
    - `03-verify-mailbox.png`
6.  Commit the changes.

### ✅ Step 4: Test the Link

1.  Go back to your main repository page (`M365-Admin-Portfolio`).
2.  Click the **"View Project"** link in your table.
3.  If everything is correct, it should open your new project page with the images showing.

### ⚠️ Troubleshooting if the Link Breaks

If you click "View Project" and get a **404 error**, it means GitHub can't find that file path. 

The most common cause is that your folders are named differently. If you previously created a folder named `Exchange Online` with a space, you have two options:

- **Option A (Fix the link):** Change the link in your main `README.md` to:
  `./Exchange%20Online/Entra%20ID/README.md`
- **Option B (Rename the folder - Recommended):** 
  1. Click into the `Exchange Online` folder.
  2. Click the settings/edit icon next to the folder name.
  3. Rename it to `01-user-mailbox-lifecycle`.
  4. Move the folder into a new folder called `projects`.

Let me know if the link works or if you get a 404, and I'll help you debug the exact path!
