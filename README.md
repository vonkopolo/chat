diff --git a/README.md b/README.md
new file mode 100644
index 0000000000000000000000000000000000000000..f9d88a08af5068b01543f3b38a8c94bb4d0cd809
--- /dev/null
+++ b/README.md
@@ -0,0 +1,31 @@
+# UcFeri Website Clone
+
+Static clone of the UcFeri landing page.
+
+## Local development
+
+Run a local server:
+
+```bash
+python3 -m http.server 4173
+```
+
+Then open:
+
+- http://127.0.0.1:4173
+
+## Deployment
+
+This repository now includes a GitHub Actions workflow at:
+
+- `.github/workflows/deploy.yml`
+
+It automatically deploys the site to **GitHub Pages** when changes are pushed to the `main` branch.
+
+### One-time GitHub setup
+
+1. Go to **Settings → Pages** in your repository.
+2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
+3. Push to `main` (or run the workflow manually via **Actions → Deploy static site to GitHub Pages → Run workflow**).
+
+After the workflow completes, your deployed site URL appears in the workflow run summary.
