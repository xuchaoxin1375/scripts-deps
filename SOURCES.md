# 转存来源

本仓库按上游版本转存 `scripts` 仓库部署时会用到的二进制，未做修改。每个 Release 附带 `LICENSE` 与 `SHA256SUMS`。

最近更新：2026-11-08

| 工具 | 上游 | 上游版本 | 本仓库 Tag | 资产 | 大小 | SHA-256 |
|---|---|---|---|---|---|---|
| argc | sigoden/argc | v1.24.0 | argc-v1.24.0 | argc-v1.24.0-x86_64-pc-windows-msvc.zip | 0.42 MB | 70f70b987cba68677db17c2012b6b7faf09a7374896b98c7ed4d039262f72914 |
| argc | sigoden/argc | v1.24.0 | argc-v1.24.0 | LICENSE-APACHE | 0.01 MB | c71d239df91726fc519c6eb72d318ec65820627232b2f796219e87dcf35d0ab4 |
| argc | sigoden/argc | v1.24.0 | argc-v1.24.0 | LICENSE-MIT | 0.00 MB | 5af431a6a9869052e2be4e71ccd731c7efe45dca47eaca84d4d1fb38f134cb79 |
| argc | sigoden/argc | v1.24.0 | argc-v1.24.0 | SHA256SUMS | 0.00 MB | 00357946995abfa6162b3501d57fa86b0b5564024201fc8d0a80fc638ae60b58 |
| argc-completions | sigoden/argc-completions | main | argc-completions-main-20261022 | argc-completions-main-19b70387.zip | 2.84 MB | 0896ead68c3b4e25ba10186069ac9ecc1eebb63ff22a512613e7f53e0e7b9224 |
| argc-completions | sigoden/argc-completions | main | argc-completions-main-20261022 | LICENSE | 0.00 MB | 2af7fe26fbe3b0e89533ba18d81c80c2fbcda6ecc71d64d5819652aa9b0d52f5 |
| argc-completions | sigoden/argc-completions | main | argc-completions-main-20261022 | SHA256SUMS | 0.00 MB | 979e1b2f722d0375c3fd09543eff0980c94b4e3d0dec0f8b2d242cd53fce51c5 |
| fzf | junegunn/fzf | v0.75.0 | fzf-v0.75.0 | fzf_0.75.0_checksums.txt | 0.00 MB | 7ac865fdb2d656f32641b4cc3f5c3b75a5afaa20e4a1c3b704df7d71dd2e0470 |
| fzf | junegunn/fzf | v0.75.0 | fzf-v0.75.0 | fzf-0.75.0-windows_amd64.zip | 2.43 MB | e3fb809d48094bea7f9f4df03b2fea33ae6e28a6cd32fdad9970cd79e1103901 |
| fzf | junegunn/fzf | v0.75.0 | fzf-v0.75.0 | LICENSE | 0.00 MB | a296f423c0d30ce3581435e78e7e36c5fe73984a882d8720c72e713b4593588b |
| fzf | junegunn/fzf | v0.75.0 | fzf-v0.75.0 | SHA256SUMS | 0.00 MB | 3c0170ca3e81b69fc03e8f3bf89b8d8d8d1e6f7e854603bd6431f0a221eee523 |
| yq | mikefarah/yq | v4.54.2 | yq-v4.54.2 | checksums | 0.11 MB | 9690309d717e793c4a6a9e871aac21fa49c83b0615d61c4f6efdd33c7cdada4f |
| yq | mikefarah/yq | v4.54.2 | yq-v4.54.2 | LICENSE | 0.00 MB | 697db34dabb21562fe84487a2ccd031fbd45382b89c2cbdec8ef31682c486040 |
| yq | mikefarah/yq | v4.54.2 | yq-v4.54.2 | SHA256SUMS | 0.00 MB | 5f1993ed9d8c52997f27e42639c0a772876dd73023ba44da1f514e41d8044ee5 |
| yq | mikefarah/yq | v4.54.2 | yq-v4.54.2 | yq_windows_amd64.exe | 15.17 MB | d14bfc4c0daf75336e07f534980b0dd560775cbffbedef29d91aa733c9fefb52 |
| zoxide | ajeetdsouza/zoxide | v0.10.0 | zoxide-v0.10.0 | LICENSE | 0.00 MB | 23aa3b08366e4ed6050f3d9950070201802aadbe5675fa1c19f24f4de91cf294 |
| zoxide | ajeetdsouza/zoxide | v0.10.0 | zoxide-v0.10.0 | SHA256SUMS | 0.00 MB | d894ee386886590b325ed891e6997a7c4c64a2e703e7158774d5c29948a2167f |
| zoxide | ajeetdsouza/zoxide | v0.10.0 | zoxide-v0.10.0 | zoxide-0.10.0-x86_64-pc-windows-msvc.zip | 0.52 MB | f465ae548f8754c8e7edbc60b45fbf58c92bfe123db83d790252d6810fa5daf1 |

## 用法

```text
https://github.com/xuchaoxin1375/scripts-deps/releases/download/<tag>/<asset>
```

## 说明

- 仅转存 Windows x86_64 产物；其他平台请直接使用上游 Release。
- 版本固定，不自动跟随上游；需要新版本时新增 tag，旧版本保留可回滚。
- 二进制版权归上游作者所有，分发遵循各 Release 内 LICENSE。
