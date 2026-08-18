+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

title = "Deep Fusion eXploration Laboratory"

# content_color = "#808080"

content_color = "#505050"


# Hero image (optional). Enter filename of an image in the `static/img/` folder.
hero_media = "logo-v-mix.png"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  color = "#ffffff"

  # Background gradient.
  # gradient_start = "#4bb4e3"
  # gradient_end = "#2b94c3"
  
  # Background image.
  # image = ""  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = false

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
# [cta]
#    url = "https://sourcethemes.com/academic/docs/install/"
#    # label = "Get Started"
#    icon_pack = "fas"
#    icon = "download"
# 这里的icon_pack和icon的使用方法详见`https://wowchemy.com/docs/getting-started/page-builder/` 中的icons一节

[[cta]]
  url = "https://developers.google.cn/machine-learning/crash-course?hl=zh-cn"
  icon_pack = "fab"
  icon = "leanpub"
  

[[cta]]
  url = "https://github.com/dfx-lab0"
  icon_pack = "fab"
  icon = "github"

# [email]
#  url = "feixiangdu@tlu.edu.cn"
#  icon = "envelope"
#  icon_pack = "fas"
+++


<div class="ipmai-content" style="text-align: justify; text-justify: inter-word;">
  <p class="sentence" data-sentence="first">Deep Fusion eXploration Laboratory(DFX-Lab) is dedicated to research in computer vision and artificial intelligence algorithms. We focus on developing novel and generalizable vision models through deep learning, feature fusion, multimodal learning, large language models, and generative models. Our research spans image segmentation, object detection, medical image analysis, and intelligent visual understanding, with an emphasis on developing efficient and robust algorithms for challenging real-world problems.</p>
  
  <p class="sentence" data-sentence="second" style="display:none;">深度融合智能探索实验室致力于计算机视觉与人工智能算法研究，重点探索深度学习、特征融合、多模态学习、大语言模型以及生成式模型等前沿技术。实验室主要研究图像分割、目标检测、医学图像分析与智能视觉理解等问题，致力于构建高性能、高效率和强泛化能力的新型视觉算法，并推动人工智能技术在实际场景中的应用。 </p>

  <!-- 切换按钮 -->
  <!-- <div class="sentence-switcher mt-3">
    <button class="btn btn-outline-primary btn-sm" onclick="switchSentence('first')"></button>
    <button class="btn btn-outline-primary btn-sm" onclick="switchSentence('second')"></button>
  </div> -->
</div>

<script>
function switchSentence(target) {
  // 隐藏所有句子
  document.querySelectorAll('.sentence').forEach(el => {
    el.style.display = 'none';
  });
  
  // 显示选中的句子
  document.querySelector(`.sentence[data-sentence="${target}"]`).style.display = 'block';
}
</script>