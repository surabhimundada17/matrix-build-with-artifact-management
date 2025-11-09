# Multi-Platform Matrix Build Demo (Workflow ID: 5974424)

This repository demonstrates a **GitHub Actions matrix build** with **artifact management**.  
Each job runs in parallel across multiple OS and Node.js versions, generates a unique build artifact,  
and uploads it using `actions/upload-artifact@v4`.

## 🧩 Workflow Details
- **Workflow File:** `.github/workflows/matrix-build.yml`
- **Matrix Dimensions:** OS × Node.js versions
- **Artifact Prefix:** `build-5974424-<variant>`
- **Identifier Step:** `matrix-5974424`
- **Artifacts:** Each job uploads a non-empty text file confirming the build details.

## 📦 Example Artifacts
```

build-5974424-ubuntu-latest-v18
build-5974424-windows-latest-v20
build-5974424-macos-latest-v22

```

Each artifact contains:
```

Build output for OS=<variant>, Node=<version>
Timestamp: <build time>
Build successful!

```

## 🧑‍💻 Maintainer
**Name:** Surabhi
**Email:** 23f2003781@ds.study.iitm.ac.in
