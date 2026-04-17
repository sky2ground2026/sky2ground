<style>
  /* This ensures all images in the real-world section have the same dimensions */
  .grid-img {
    width: 32%;
    height: 200px; /* Adjust this height as you prefer */
    object-fit: cover;
    border-radius: 4px;
    margin-bottom: 5px;
  }
</style>
<div align="center">
  <h1>Sky2Ground: A Benchmark for Site Modeling under Varying Altitude</h1>

  <p>
    <b>Zengyan Wang</b>, 
    <b>Sirshapan Mitra</b>, 
    <a href="https://rajatmodi62.github.io/2026/04/09/sky2ground/"><b>Rajat Modi</b></a>, 
    <b>Grace Lim</b>,
    <b>Yogesh Rawat</b>
    <br>
    <strong>CVPR 2026</strong>
    <br>
    <a href="https://arxiv.org/abs/2603.13740">[arXiv]</a> | 
    <a href="https://www.kaggle.com/datasets/zhyw86/varying-altitude-dataset">[Dataset]</a> | 
    <a href="https://github.com/zhyw86/Sky2Ground">[Code]</a>
  </p>

  <hr>

  <h2>🖼 Dataset Preview</h2>
  <p>Our dataset bridges the gap between synthetic environments and real-world captures. Below are samples of the multi-view perspectives provided.</p>

  <h3>🌐 Synthetic Dataset (GIF Samples)</h3>
  <p><i>Generated environments featuring a full 5-view suite.</i></p>

  <p>
    <img src="gif/ID0004_satellite.gif" width="19%" title="Synthetic Satellite">
    <img src="gif/ID0004_left.gif" width="19%" title="Synthetic Aerial Left">
    <img src="gif/ID0004.gif" width="19%" title="Synthetic Aerial Center">
    <img src="gif/ID0004_right.gif" width="19%" title="Synthetic Aerial Right">
    <img src="gif/ID0004_street.gif" width="19%" title="Synthetic Street View">
    <br>
    <em>Satellite | Aerial L | Aerial C | Aerial R | Street View</em>
  </p>

  <hr>

  <h3>📸 Real-World Dataset (Static Images)</h3>
  <p><i>Authentic captures for domain validation.</i></p>

<p>
    <img src="imgs/ID0004_sat_real_19.jpg" class="grid-img" title="Real Satellite">
    <img src="imgs/aerial_014.jpg" class="grid-img" title="Real Aerial 1">
    <img src="imgs/aerial_019.jpg" class="grid-img" title="Real Aerial 2">
    <br>
    <img src="imgs/street_003.jpg" class="grid-img" title="Real Street View 1">
    <img src="imgs/street_033.jpg" class="grid-img" title="Real Street View 2">
    <img src="imgs/street_120.jpg" class="grid-img" title="Real Street View 3">
    <br>
    <em>Top: Satellite & Aerial Views | Bottom: Street Views</em>
  </p>

  <blockquote style="background: #f9f9f9; border-left: 10px solid #ccc; margin: 1.5em 10px; padding: 0.5em 10px; text-align: left;">
    <strong>Note:</strong> Real-world samples are provided as high-resolution static images, while synthetic samples include dynamic transitions (GIFs) to demonstrate environmental variance.
  </blockquote>
</div>

<div align="left">
  <hr>
  <h2>🚀 Access the Dataset</h2>

  <table border="1" cellpadding="10" style="border-collapse: collapse; width: 100%; text-align: left;">
    <thead>
      <tr style="background-color: #f2f2f2;">
        <th>Platform</th>
        <th>Link</th>
        <th>Recommended For</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><b>Hugging Face</b></td>
        <td><a href="https://huggingface.co/datasets/letsGoBlind/Sky2Ground/tree/main">🤗 Under Construction</a></td>
        <td></td>
      </tr>
      <tr>
        <td><b>Kaggle</b></td>
        <td><a href="https://www.kaggle.com/datasets/zhyw86/varying-altitude-dataset">📁 Under Construction</a></td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <hr>

  <h2>🛠 Project Progress</h2>
  <ul style="list-style: none; padding-left: 0;">
    <li>✅ Synthetic Images</li>
    <li>⬜ Real Images</li>
    <li>⬜ Benchmark</li>
  </ul>

  <hr>

  <h2>Citation</h2>
  <div style="background-color: #f6f8fa; padding: 15px; border-radius: 6px; font-family: monospace; overflow-x: auto;">
    <pre><code>@misc{wang2026sky2groundbenchmarksitemodeling,
      title={Sky2Ground: A Benchmark for Site Modeling under Varying Altitude}, 
      author={Zengyan Wang and Sirshapan Mitra and Rajat Modi and Grace Lim and Yogesh Rawat},
      year={2026},
      eprint={2603.13740},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2603.13740}
}</code></pre>
  </div>
</div>
