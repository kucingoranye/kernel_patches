### 🇮🇩 Indonesia
Setelah melakukan patch, pastikan ini aktif pada defconfig <code>CONFIG_TCP_CONG_ADVANCED=y</code> kemudian tambahkan:
<br>

<ul>
  <li>
    <b>BBR V3</b><br>
    <code>CONFIG_TCP_CONG_BBR=y</code><br>
    Contoh penerapan: <a href="https://github.com/kucingoranye/android_kernel_xiaomi_sdm660_419/commit/578d9205499b194fb9204bef2ec9c610e9403f9d" target="_blank">578d920</a>
  </li>
  <br>
  <li>
    <b>BBR Plus</b><br>
    <code>CONFIG_TCP_CONG_BBRPLUS=y</code><br>
    Contoh penerapan: <a href="https://github.com/kucingoranye/android_kernel_xiaomi_sdm660_419/commit/4fa179075af98a1f0bafde8ccb81bce27115bc1c" target="_blank">4fa1790</a>
  </li>
</ul>

---

### 🌐 English
After patching, make sure to enable <code>CONFIG_TCP_CONG_ADVANCED=y</code> in your defconfig, then add these:
<br>

<ul>
  <li>
    <b>BBR V3</b><br>
    <code>CONFIG_TCP_CONG_BBR=y</code><br>
    Example: <a href="https://github.com/kucingoranye/android_kernel_xiaomi_sdm660_419/commit/578d9205499b194fb9204bef2ec9c610e9403f9d" target="_blank">578d920</a>
  </li>
  <br>
  <li>
    <b>BBR Plus</b><br>
    <code>CONFIG_TCP_CONG_BBRPLUS=y</code><br>
    Example: <a href="https://github.com/kucingoranye/android_kernel_xiaomi_sdm660_419/commit/4fa179075af98a1f0bafde8ccb81bce27115bc1c" target="_blank">4fa1790</a>
  </li>
</ul>
