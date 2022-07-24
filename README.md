# 🎨 UI

Deploy [Navi UI (Nuxt.js)](https://nuxtjs.org) project to Vercel with zero configuration.

<!-- [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/vercel/tree/main/examples/nuxtjs&template=nuxtjs) -->

<!-- _Live Example: https://nuxtjs-template.vercel.app_ -->

<!-- #region drawnote -->
<svg id="svg" xmlns="http://www.w3.org/2000/svg" viewbox="7.950000762939453,-7.450000047683716,752.4500122070312,429.510009765625" style="height:300.510009765625"><polygon points="121.59 412.06" fill="gray" stroke="blue" stroke-width="2" d="M 121.59 412.06 L  Z"></polygon><polygon points="469.38 54.085, 355.87 68.03, 242.36 54.085, 355.87 40.14" fill="gray" stroke="lightblue" stroke-width="2" d="M 469.38 54.085 L ,  355.87 68.03 ,  242.36 54.085 ,  355.87 40.14 Z"></polygon><polygon points="122.23 63.025000000000006, 238.02 55.52, 353.81 63.025000000000006, 238.02 70.53" fill="gray" stroke="lightgreen" stroke-width="2" d="M 122.23 63.025000000000006 L ,  238.02 55.52 ,  353.81 63.025000000000006 ,  238.02 70.53 Z"></polygon><polygon points="692.98 67.25999999999999, 525.4300000000001 94.86, 357.88 67.25999999999999, 525.4300000000001 39.66" fill="gray" stroke="lightgreen" stroke-width="2" d="M 692.98 67.25999999999999 L ,  525.4300000000001 94.86 ,  357.88 67.25999999999999 ,  525.4300000000001 39.66 Z"></polygon><polygon points="654.69 109.82, 447.96000000000004 147.81, 241.23 109.82, 447.96000000000004 71.83" fill="white" stroke="lightblue" stroke-width="2" d="M 654.69 109.82 L ,  447.96000000000004 147.81 ,  241.23 109.82 ,  447.96000000000004 71.83 Z"></polygon><polygon points="464.37 77.255, 307.495 88.06, 150.62 77.255, 307.495 66.45" fill="white" stroke="lightblue" stroke-width="2" d="M 464.37 77.255 L ,  307.495 88.06 ,  150.62 77.255 ,  307.495 66.45 Z"></polygon><polygon points="49.15 157.765, 81.32 151.37, 113.49 157.765, 81.32 164.16" fill="gray" stroke="lightgreen" stroke-width="2" d="M 49.15 157.765 L ,  81.32 151.37 ,  113.49 157.765 ,  81.32 164.16 Z"></polygon><polygon points="83.6 109.035, 83.345 68.46, 83.09 109.035, 83.345 149.61" fill="white" stroke="lightblue" stroke-width="2" d="M 83.6 109.035 L ,  83.345 68.46 ,  83.09 109.035 ,  83.345 149.61 Z"></polygon><polygon points="123.22 64.065, 104.35 58.58, 85.48 64.065, 104.35 69.55" fill="gray" stroke="lightgreen" stroke-width="2" d="M 123.22 64.065 L ,  104.35 58.58 ,  85.48 64.065 ,  104.35 69.55 Z"></polygon><polygon points="275.24 157.735, 193.565 156.3, 111.89 157.735, 193.565 159.17" fill="lightblue" stroke="lightgreen" stroke-width="2" d="M 275.24 157.735 L ,  193.565 156.3 ,  111.89 157.735 ,  193.565 159.17 Z"></polygon><polygon points="447.97 159.56, 362.005 160.59, 276.04 159.56, 362.005 158.53" fill="gray" stroke="pink" stroke-width="2" d="M 447.97 159.56 L ,  362.005 160.59 ,  276.04 159.56 ,  362.005 158.53 Z"></polygon><polygon points="426.22 76.57, 442.25 72.71, 458.28 76.57, 442.25 80.43" fill="white" stroke="lightgreen" stroke-width="2" d="M 426.22 76.57 L ,  442.25 72.71 ,  458.28 76.57 ,  442.25 80.43 Z"></polygon><polygon points="450.85 76.74000000000001, 444.67 71.56, 438.49 76.74000000000001, 444.67 81.92" fill="black" stroke="lightgreen" stroke-width="2" d="M 450.85 76.74000000000001 L ,  444.67 71.56 ,  438.49 76.74000000000001 ,  444.67 81.92 Z"></polygon><polygon points="429.79 75.295, 444.905 72.56, 460.02 75.295, 444.905 78.03" fill="gray" stroke="lightgreen" stroke-width="2" d="M 429.79 75.295 L ,  444.905 72.56 ,  460.02 75.295 ,  444.905 78.03 Z"></polygon><polygon points="432.52 77.60499999999999, 439.115 73.58, 445.71 77.60499999999999, 439.115 81.63" fill="gray" stroke="lightgreen" stroke-width="2" d="M 432.52 77.60499999999999 L ,  439.115 73.58 ,  445.71 77.60499999999999 ,  439.115 81.63 Z"></polygon><polygon points="459.83 74.68, 446.84000000000003 72.11, 433.85 74.68, 446.84000000000003 77.25" fill="gray" stroke="lightgreen" stroke-width="2" d="M 459.83 74.68 L ,  446.84000000000003 72.11 ,  433.85 74.68 ,  446.84000000000003 77.25 Z"></polygon><polygon points="436.09 75.56, 446.51 71.58, 456.93 75.56, 446.51 79.54" fill="gray" stroke="lightgreen" stroke-width="2" d="M 436.09 75.56 L ,  446.51 71.58 ,  456.93 75.56 ,  446.51 79.54 Z"></polygon><polygon points="453.46 76.32499999999999, 440.475 74.35, 427.49 76.32499999999999, 440.475 78.3" fill="gray" stroke="lightgreen" stroke-width="2" d="M 453.46 76.32499999999999 L ,  440.475 74.35 ,  427.49 76.32499999999999 ,  440.475 78.3 Z"></polygon><polygon points="437.52 77.305, 444.71 79.36, 451.9 77.305, 444.71 75.25" fill="gray" stroke="lightgreen" stroke-width="2" d="M 437.52 77.305 L ,  444.71 79.36 ,  451.9 77.305 ,  444.71 75.25 Z"></polygon><polygon points="81.77 109.435, 161.98499999999999 107.83, 242.2 109.435, 161.98499999999999 111.04" fill="gray" stroke="lightgreen" stroke-width="2" d="M 81.77 109.435 L ,  161.98499999999999 107.83 ,  242.2 109.435 ,  161.98499999999999 111.04 Z"></polygon><polygon points="233.46 71.29, 169.845 70.43, 106.23 71.29, 169.845 72.15" fill="gray" stroke="lightgreen" stroke-width="2" d="M 233.46 71.29 L ,  169.845 70.43 ,  106.23 71.29 ,  169.845 72.15 Z"></polygon><polygon points="36 74.88999999999999, 96.69 70.96, 157.38 74.88999999999999, 96.69 78.82" fill="gray" stroke="lightgreen" stroke-width="2" d="M 36 74.88999999999999 L ,  96.69 70.96 ,  157.38 74.88999999999999 ,  96.69 78.82 Z"></polygon><polygon points="370.01 88.42500000000001, 233.885 94.68, 97.76 88.42500000000001, 233.885 82.17" fill="gray" stroke="lightgreen" stroke-width="2" d="M 370.01 88.42500000000001 L ,  233.885 94.68 ,  97.76 88.42500000000001 ,  233.885 82.17 Z"></polygon><polygon points="750.4 154.21499999999997, 432.325 149.01, 114.25 154.21499999999997, 432.325 159.42" fill="white" stroke="lightgreen" stroke-width="2"></polygon><polygon points="750.4 149.01" fill="black" stroke="lightgreen" stroke-width="2" d="M 750.4 149.01 L  Z"></polygon><polygon points="363.73 88.82, 401.37 88.2, 439.01 88.82, 401.37 89.44" fill="black" stroke="lightgreen" stroke-width="2" d="M 363.73 88.82 L ,  401.37 88.2 ,  439.01 88.82 ,  401.37 89.44 Z"></polygon><polygon points="526.13 78.575, 447.2 70.67, 368.27 78.575, 447.2 86.48" fill="gray" stroke="lightgreen" stroke-width="2" d="M 526.13 78.575 L ,  447.2 70.67 ,  368.27 78.575 ,  447.2 86.48 Z"></polygon><polygon points="421.35 82.36500000000001, 391.20000000000005 76.42, 361.05 82.36500000000001, 391.20000000000005 88.31" fill="gray" stroke="lightgreen" stroke-width="2" d="M 421.35 82.36500000000001 L ,  391.20000000000005 76.42 ,  361.05 82.36500000000001 ,  391.20000000000005 88.31 Z"></polygon><polygon points="498.99 91.12, 444.73 94.6, 390.47 91.12, 444.73 87.64" fill="gray" stroke="lightgreen" stroke-width="2" d="M 498.99 91.12 L ,  444.73 94.6 ,  390.47 91.12 ,  444.73 87.64 Z"></polygon><polygon points="312.08 90.175, 371.35 96.75, 430.62 90.175, 371.35 83.6" fill="black" stroke="lightgreen" stroke-width="2" d="M 312.08 90.175 L ,  371.35 96.75 ,  430.62 90.175 ,  371.35 83.6 Z"></polygon><polygon points="214.69 83.94999999999999, 150.41 87.02, 86.13 83.94999999999999, 150.41 80.88" fill="black" stroke="lightgreen" stroke-width="2" d="M 214.69 83.94999999999999 L ,  150.41 87.02 ,  86.13 83.94999999999999 ,  150.41 80.88 Z"></polygon><polygon points="335.54 91.75, 210.15 70.45, 84.76 91.75, 210.15 113.05" fill="gray" stroke="lightgreen" stroke-width="2" d="M 335.54 91.75 L ,  210.15 70.45 ,  84.76 91.75 ,  210.15 113.05 Z"></polygon><polygon points="28.43 93.285, 101.44500000000001 76.95, 174.46 93.285, 101.44500000000001 109.62" fill="gray" stroke="lightgreen" stroke-width="2" d="M 28.43 93.285 L ,  101.44500000000001 76.95 ,  174.46 93.285 ,  101.44500000000001 109.62 Z"></polygon><polygon points="40.38 60.650000000000006, 127.02499999999999 48.68, 213.67 60.650000000000006, 127.02499999999999 72.62" fill="black" stroke="lightgreen" stroke-width="2" d="M 40.38 60.650000000000006 L ,  127.02499999999999 48.68 ,  213.67 60.650000000000006 ,  127.02499999999999 72.62 Z"></polygon><polygon points="17.95 79.41499999999999, 31.86 96.05, 45.77 79.41499999999999, 31.86 62.78" fill="black" stroke="lightgreen" stroke-width="2" d="M 17.95 79.41499999999999 L ,  31.86 96.05 ,  45.77 79.41499999999999 ,  31.86 62.78 Z"></polygon><polygon points="689.28 53.254999999999995, 367.34 25.38, 45.4 53.254999999999995, 367.34 81.13" fill="gray" stroke="lightgreen" stroke-width="2" d="M 689.28 53.254999999999995 L ,  367.34 25.38 ,  45.4 53.254999999999995 ,  367.34 81.13 Z"></polygon><polygon points="691.04 60.855, 689.66 67.91, 688.28 60.855, 689.66 53.8" fill="black" stroke="lightgreen" stroke-width="2" d="M 691.04 60.855 L ,  689.66 67.91 ,  688.28 60.855 ,  689.66 53.8 Z"></polygon><polygon points="692.3 116.77, 691.935 162.76, 691.57 116.77, 691.935 70.78" fill="black" stroke="lightgreen" stroke-width="2" d="M 692.3 116.77 L ,  691.935 162.76 ,  691.57 116.77 ,  691.935 70.78 Z"></polygon><polygon points="689.91 157.07999999999998, 692.1099999999999 149.96, 694.31 157.07999999999998, 692.1099999999999 164.2" fill="black" stroke="lightgreen" stroke-width="2" d="M 689.91 157.07999999999998 L ,  692.1099999999999 149.96 ,  694.31 157.07999999999998 ,  692.1099999999999 164.2 Z"></polygon><polygon points="689.6 74.27000000000001, 691.72 81.98, 693.84 74.27000000000001, 691.72 66.56" fill="black" stroke="lightgreen" stroke-width="2" d="M 689.6 74.27000000000001 L ,  691.72 81.98 ,  693.84 74.27000000000001 ,  691.72 66.56 Z"></polygon><polygon points="744.59 54.205, 707.54 51.09, 670.49 54.205, 707.54 57.32" fill="black" stroke="lightgreen" stroke-width="2" d="M 744.59 54.205 L ,  707.54 51.09 ,  670.49 54.205 ,  707.54 57.32 Z"></polygon><polygon points="639.42 59, 662.06 60.66, 684.7 59, 662.06 57.34" fill="black" stroke="lightgreen" stroke-width="2" d="M 639.42 59 L ,  662.06 60.66 ,  684.7 59 ,  662.06 57.34 Z"></polygon><polygon points="708.9 58.12, 674.96 56.19, 641.02 58.12, 674.96 60.05" fill="black" stroke="lightgreen" stroke-width="2" d="M 708.9 58.12 L ,  674.96 56.19 ,  641.02 58.12 ,  674.96 60.05 Z"></polygon><polygon points="695.05 62.739999999999995, 690.76 57.21, 686.47 62.739999999999995, 690.76 68.27" fill="black" stroke="lightgreen" stroke-width="2" d="M 695.05 62.739999999999995 L ,  690.76 57.21 ,  686.47 62.739999999999995 ,  690.76 68.27 Z"></polygon><polygon points="684.5 58.075, 675.575 58.81, 666.65 58.075, 675.575 57.34" fill="black" stroke="lightgreen" stroke-width="2" d="M 684.5 58.075 L ,  675.575 58.81 ,  666.65 58.075 ,  675.575 57.34 Z"></polygon><polygon points="696.32 59.035, 679.485 58.67, 662.65 59.035, 679.485 59.4" fill="black" stroke="lightgreen" stroke-width="2" d="M 696.32 59.035 L ,  679.485 58.67 ,  662.65 59.035 ,  679.485 59.4 Z"></polygon><polygon points="685.75 59.325, 672.9100000000001 59.35, 660.07 59.325, 672.9100000000001 59.3" fill="black" stroke="lightgreen" stroke-width="2" d="M 685.75 59.325 L ,  672.9100000000001 59.35 ,  660.07 59.325 ,  672.9100000000001 59.3 Z"></polygon><polygon points="694 53.72, 690.7 39.38, 687.4 53.72, 690.7 68.06" fill="black" stroke="lightgreen" stroke-width="2" d="M 694 53.72 L ,  690.7 39.38 ,  687.4 53.72 ,  690.7 68.06 Z"></polygon><polygon points="361.47 119.45, 366.54 158.21, 371.61 119.45, 366.54 80.69" fill="black" stroke="lightgreen" stroke-width="2" d="M 361.47 119.45 L ,  366.54 158.21 ,  371.61 119.45 ,  366.54 80.69 Z"></polygon><polygon points="353.59 25.995, 348.985 9.25, 344.38 25.995, 348.985 42.74" fill="black" stroke="lightgreen" stroke-width="2" d="M 353.59 25.995 L ,  348.985 9.25 ,  344.38 25.995 ,  348.985 42.74 Z"></polygon><polygon points="337.27 8.219999999999999, 348.78999999999996 4.42, 360.31 8.219999999999999, 348.78999999999996 12.02" fill="black" stroke="lightgreen" stroke-width="2" d="M 337.27 8.219999999999999 L ,  348.78999999999996 4.42 ,  360.31 8.219999999999999 ,  348.78999999999996 12.02 Z"></polygon><polygon points="338.52 25.43, 343.79499999999996 38.12, 349.07 25.43, 343.79499999999996 12.74" fill="black" stroke="lightgreen" stroke-width="2" d="M 338.52 25.43 L ,  343.79499999999996 38.12 ,  349.07 25.43 ,  343.79499999999996 12.74 Z"></polygon><polygon points="311.23 27.565, 329.08000000000004 31.26, 346.93 27.565, 329.08000000000004 23.87" fill="black" stroke="lightgreen" stroke-width="2" d="M 311.23 27.565 L ,  329.08000000000004 31.26 ,  346.93 27.565 ,  329.08000000000004 23.87 Z"></polygon><polygon points="375.35 31.11, 360.18 35.09, 345.01 31.11, 360.18 27.13" fill="black" stroke="lightgreen" stroke-width="2" d="M 375.35 31.11 L ,  360.18 35.09 ,  345.01 31.11 ,  360.18 27.13 Z"></polygon><polygon points="356.85 23.01, 348.68 12.99, 340.51 23.01, 348.68 33.03" fill="black" stroke="lightgreen" stroke-width="2" d="M 356.85 23.01 L ,  348.68 12.99 ,  340.51 23.01 ,  348.68 33.03 Z"></polygon><polygon points="299.23 20.39, 327.96000000000004 27.92, 356.69 20.39, 327.96000000000004 12.86" fill="black" stroke="lightgreen" stroke-width="2" d="M 299.23 20.39 L ,  327.96000000000004 27.92 ,  356.69 20.39 ,  327.96000000000004 12.86 Z"></polygon><polygon points="309.19 2.55" fill="black" stroke="lightgreen" stroke-width="2" d="M 309.19 2.55 L  Z"></polygon><polygon points="309.19 2.55" fill="black" stroke="lightgreen" stroke-width="2" d="M 309.19 2.55 L  Z"></polygon><polygon points="373.18 16.28, 338.435 23.39, 303.69 16.28, 338.435 9.17" fill="black" stroke="lightgreen" stroke-width="2" d="M 373.18 16.28 L ,  338.435 23.39 ,  303.69 16.28 ,  338.435 9.17 Z"></polygon><polygon points="305.36 12.24, 348.045 16.87, 390.73 12.24, 348.045 7.61" fill="black" stroke="lightgreen" stroke-width="2" d="M 305.36 12.24 L ,  348.045 16.87 ,  390.73 12.24 ,  348.045 7.61 Z"></polygon><polygon points="393.43 11.629999999999999, 345.69 14.16, 297.95 11.629999999999999, 345.69 9.1" fill="black" stroke="lightgreen" stroke-width="2" d="M 393.43 11.629999999999999 L ,  345.69 14.16 ,  297.95 11.629999999999999 ,  345.69 9.1 Z"></polygon><polygon points="306.63 7.33, 353.275 4.43, 399.92 7.33, 353.275 10.23" fill="black" stroke="lightgreen" stroke-width="2" d="M 306.63 7.33 L ,  353.275 4.43 ,  399.92 7.33 ,  353.275 10.23 Z"></polygon></svg>  
<!-- #endregion -->

Unified UI and Design Kit for Navi.
## 📦 Packages

<table>
  <tbody>
    <tr>
      <td>
        <h2><a href="./packages/ui">UI Components</a></h2>
        <p>UI kit for examples and internal tooling UI. Demo on <a href="https://components.ui.conda.app">components.ui.conda.app</a></p>
      </td>
      <td>
        <h2><a href="./packages/templates">UI Templates</a></h2>
        <p>Pre-compiled html templates for internal pages. Demo on <a href="https://templates.ui.conda.app">templates.ui.codna.app</a></p>
      </td>
      <td>
        <h2><a href="./packages/assets">UI Assets</a></h2>
        <p>Shared assets and resources.</p>
      </td>
    </tr>
  </tbody>
</table>

## 💻 Development

- Clone repository
- Enable [Corepack](https://github.com/nodejs/corepack) using `corepack enable` (use `npm i -g corepack` for Node.js < 16.10)
- Install dependencies using `yarn install`
