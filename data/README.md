---
language:
- en
license: mit
task_categories:
- object-detection
pretty_name: ExposureEngine
tags:
- Oriented Logo Detection
- Oriented Object Detection
- Sponsor Visibility
- logo
- detection
---

# ExposureEngine: Oriented Logo Detection & Sponsor Visibility Analytics (Dataset)

[Paper](https://huggingface.co/papers/2510.04739) | [Project Page](https://youtu.be/tRw6OBISuW4)

<div style="font-family: Inter, -apple-system, Segoe UI, Roboto, Helvetica, Arial, sans-serif; max-width: 940px; margin: 0 auto; line-height: 1.55; color: inherit; text-align: left;">

  <div style="border:1px solid #ccc; border-radius: 12px; padding: 22px 24px; color: inherit;">
    <p style="margin: 0;">Rotation-aware <strong>OBB</strong> annotations for sponsor logos in professional soccer broadcasts — built for <strong>sports analytics</strong>, <strong>YOLO OBB training</strong>, and <strong>sponsorship measurement</strong>.</p>
  </div>

  <div style="display: flex; gap: 10px; flex-wrap: wrap; margin: 14px 0 22px;">
    <span style="border:1px solid #ccc; padding:6px 10px; border-radius:999px; font-size:12px; color: inherit;">Oriented Bounding Boxes</span>
    <span style="border:1px solid #ccc; padding:6px 10px; border-radius:999px; font-size:12px; color: inherit;">Sports Broadcasts</span>
    <span style="border:1px solid #ccc; padding:6px 10px; border-radius:999px; font-size:12px; color: inherit;">Sponsorship Analytics</span>
    <span style="border:1px solid #ccc; padding:6px 10px; border-radius:999px; font-size:12px; color: inherit;">YOLOv8/YOLOv11 OBB</span>
    <span style="border:1px solid #ccc; padding:6px 10px; border-radius:999px; font-size:12px; color: inherit;">Brand Visibility</span>
  </div>

  <div style="border:1px solid #ccc; border-radius: 12px; padding: 22px 24px; color: inherit;">
    <p><strong>ExposureEngine</strong> provides high-quality <em>oriented bounding box (OBB)</em> polygon annotations of sponsor logos from professional soccer footage to enable accurate <strong>sponsor visibility measurement</strong>, <strong>logo tracking</strong>, and <strong>rotation-aware detection</strong>.</p>
  </div>

  <div style="border: 1px solid #ccc; border-radius: 12px; padding: 16px 18px; margin-top: 18px;">
    <h2 style="margin: 0 0 10px; font-size: 20px;">📂 Dataset Overview</h2>
    <ul style="margin: 0; padding-left: 18px;">
      <li><strong>Source:</strong> 97 broadcast highlight clips from the <em>2024 Swedish Elite Soccer League</em></li>
      <li><strong>Frames:</strong> 1,103 curated frames (sampled at 1 FPS)</li>
      <li><strong>Annotations:</strong> 670 unique sponsor logos with <strong>OBB polygon coordinates</strong> (YOLO format)</li>
      <li><strong>Coverage:</strong> 32 matches · 16 teams · diverse events: Goals, Shots, Yellow Cards, Offsides, Substitutions</li>
      <li><strong>Splits:</strong> Train / Validation / Test = <strong>80 / 10 / 10</strong></li>
    </ul>
  </div>

  <div style="border:1px solid #ccc; border-radius:12px; padding:14px 16px; margin-top:18px;">
    <h2 style="margin:0 0 10px; font-size:20px;">🔍 Why Oriented Bounding Boxes?</h2>
    <p style="margin:0;">OBB captures <strong>rotation</strong>, <strong>skew</strong>, and <strong>perspective</strong> — common in sports due to dynamic camera angles, jersey folds, and slanted boards. This improves <strong>coverage accuracy</strong> and <strong>downstream analytics</strong> over traditional HBB.</p>
  </div>

  <div style="border:1px solid #ccc; border-radius:12px; padding:14px 16px; margin-top:18px;">
    <h2 style="margin:0 0 10px; font-size:20px;">🚀 Applications</h2>
    <ul style="margin:0; padding-left:18px;">
      <li>Sports <strong>sponsorship analytics</strong> & reporting</li>
      <li><strong>YOLO-based</strong> OBB training & benchmarking</li>
      <li>Brand <strong>visibility measurement</strong> in broadcasts</li>
      <li>Content adaptation for <strong>social media</strong> & OTT</li>
    </ul>
  </div>

  <div style="border: 1px solid #ccc; border-radius: 12px; padding: 14px 16px; margin-top: 18px;">
    <h2 style="margin:0 0 10px; font-size:20px;">⚡ Quick Start (🤗 Datasets)</h2>
    <pre style="margin:0; background:transparent; color: inherit; padding:12px 14px; border-radius:10px; border:1px solid #ccc; overflow:auto;"><code>from datasets import load_dataset

dataset = load_dataset("SimulaMet-HOST/ExposureEngine")
print(dataset)</code></pre>
    <p style="margin:10px 0 0; font-size:14px;">Each label file contains <strong>four-corner polygon coordinates</strong> per logo in <em>YOLO OBB</em> format.</p>
  </div>

  <div style="border:1px solid #ccc; border-radius:12px; padding:14px 16px; margin-top:18px;">
    <h2 style="margin:0 0 10px; font-size:20px;">📄 Citation</h2>
    <p style="margin:0;">If you use this dataset, please cite the paper:</p>
    <p style="margin:8px 0 0;"><em><a href="https://huggingface.co/papers/2510.04739" style="color: inherit; text-decoration: underline;">ExposureEngine: Oriented Logo Detection and Sponsor Visibility Analytics in Sports Broadcasts</a>.</em></p>
  </div>

  <div style="border:1px solid #ccc; border-radius:12px; padding:14px 16px; margin-top:18px;">
    <h2 style="margin:0 0 10px; font-size:20px;">📬 Contact</h2>
    <p style="margin:0;">Email: <a href="mailto:mehdi@forzasys.com" style="color: inherit; text-decoration: underline;">mehdi@forzasys.com</a></p>
  </div>

</div>