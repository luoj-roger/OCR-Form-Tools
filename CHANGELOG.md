# FoTT Changelog 

## 2.0.0-814276a (05-20-2020)
* fix: modify skip button according to feedback comments ([#264](https://github.com/microsoft/OCR-Form-Tools/commit/814276af6f4259844854798adf0c56bd606b2363))
* feature: keyboard shortcuts and tips ([#258](https://github.com/microsoft/OCR-Form-Tools/commit/37aa859a80dc0213a118313558ad21ba424008e7))
* feat: add electron mode from VoTT project ([#260](https://github.com/microsoft/OCR-Form-Tools/commit/2a3383d4a0f100a39ed40627bdffb9b48f78f5df))
* refactor: use forEach instead of map in handleFeatureSelect ([#259](https://github.com/microsoft/OCR-Form-Tools/commit/c1c590c463743d187fda2429a628e27c6c42012f))

## 2.0.0-0061645 (05-13-2020)
* build: update nginx base image version to 1.18.0-alpine ([#255](https://github.com/microsoft/OCR-Form-Tools/commit/0061645871806595e4fe2ab5991cc494afa26b31))
* fix: assign empty string when predict item's fieldName is undefined ([#254](https://github.com/microsoft/OCR-Form-Tools/commit/d4d919f678b1f162f48c87ee5223281e57945a0a))
* fix: overlaping left split pane ([#252](https://github.com/microsoft/OCR-Form-Tools/commit/2e8c351f74c385b8627ee6ea39f974e5e048ea8d))
* refactor: change predict to analyze in UI while keeping predict term ([#147](https://github.com/microsoft/OCR-Form-Tools/commit/c9aa58e36a10a35083249a8080c2cfb9fccf3733))
## 2.0.0-7c7ba93 (05-07-2020)
* fix: check null value from post processed value ([#248](https://github.com/microsoft/OCR-Form-Tools/commit/a361189c527bfffd6417f90a2521ad40b2b3f205))
* feat: enable outputting to file for analyze script ([#246](https://github.com/microsoft/OCR-Form-Tools/commit/7c7ba937f140490775b788d63ef2c7ed63ca40f1))
## 2.0.0-9d91800 (05-06-2020)
* fix: prevent user from changing tag types when invalid ([#224](https://github.com/microsoft/OCR-Form-Tools/commit/d8823a33591db5c5dc9a0af753e007167218a3e3))
* fix: prevent user from adding multiple checkboxes to a single tag ([#224](https://github.com/microsoft/OCR-Form-Tools/commit/d8823a33591db5c5dc9a0af753e007167218a3e3))
* fix: display error when inputted SAS doesn't contain token ([#243](https://github.com/microsoft/OCR-Form-Tools/commit/9826ca8504549f23057c9cad1baebc5e9d1f6fe7))
## 2.0.0-25d3298 (05-04-2020)
* feat: track document count for tags ([#231](https://github.com/microsoft/OCR-Form-Tools/commit/70a6e43dc54239cdc153d5d328b17c1dfa0f085f))
* fix: display error when inputted service URI contains path or query ([#234](https://github.com/microsoft/OCR-Form-Tools/commit/04a16961b37ad5b5d01fc4c93addaaf69cbf0e72))
* feat: add link in status bar to CHANGELOG ([#233](https://github.com/microsoft/OCR-Form-Tools/commit/e66646a13263239213580378bbd2d8462d7e22b6))
## 2.0.0-f6c8ffa (05-01-2020)
* refactor: change checkbox to selectionMark ([#223](https://github.com/microsoft/OCR-Form-Tools/commit/f6c8ffad6edf23f6241f314e9456da92bc1a8402))
## 2.0.0-f3e42f6 (04-30-2020)
* feat: display post-processed value in analyzed results ([#229](https://github.com/microsoft/OCR-Form-Tools/commit/f3e42f6e8e9e934f1a241921dbe4a1e8d311bb46))
## 2.0.0-f068866 (04-28-2020)
* fix: hide sprin in tag input control when open an empty folder ([#220](https://github.com/microsoft/OCR-Form-Tools/commit/f0688668df2e676fce9749fad8ec9d39e56697cf))
* perf: cache images, reduce canvas size, and fix memory leak for asset preview ([#218](https://github.com/microsoft/OCR-Form-Tools/commit/e8ad9a3bebf2a1ae210e0e1fa3eebba564592c4c))
## 2.0.0-595a512 (04-24-2020)
* fix: align rotated picture asset with OCR result
## 2.0.0-51c02cc (04-20-2020)
* fix: scrollbar fix when page size changes
* fix: Add split pane to fix too long tag name is invisible in right sidebar
## 2.0.0-202fb2f (04-20-2020)
* perf: improve assets loading performance and fix some bugs
## 2.0.0-bce554e (04-16-2020)
* perf: improve Azure Blob file list performance
* feat: support URL upload for predicting file
## 2.0.0-ef18425 (04-09-2020)
* feat: enable checkbox labeling (preview)
