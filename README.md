# DDRescue GUI Compiler

Automated cloud compilation framework node built to package the latest stable source code releases of DDRescue-GUI into a native system installer wrapper (`.deb`) for **Ubuntu 26.04**.

## 🛠️ How To Compile on Your Own GitHub Profile

Because this is a public automation node, the manual execution configurations are sandboxed to individual user accounts. To run this compiler framework on your own profile:

1. Click the **Fork** button at the top right of this repository page to create a personal copy under your own account layout.
2. Navigate directly to the upper **Actions** manager menu tab inside your new forked repository.
3. Select the **Compile Latest DDRescue-GUI DEB Package** workflow sequence from the left sidebar tree.
4. Click the **Run workflow** dropdown button on the right side of the layout screen.
5. Once the cloud server container finish pass executes, download your fresh production compiler artifact zip file directly from the bottom of the log screen.

## 🚀 Local Desktop Installation

Extract the completed installer package onto your local machine workspace and run the system deployment pass through your console to audit the file dependencies manually:

```bash
sudo apt install ./ddrescue-gui-custom_*.deb
```
