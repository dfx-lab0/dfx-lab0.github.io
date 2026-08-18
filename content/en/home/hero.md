+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

title = "IPMAI-Lab"

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
  url = "https://github.com/IPMAI-Lab"
  icon_pack = "fab"
  icon = "github"

# [email]
#  url = "feixiangdu@tlu.edu.cn"
#  icon = "envelope"
#  icon_pack = "fas"
+++


<div class="ipmai-content" style="text-align: justify; text-justify: inter-word;">
  <p class="sentence" data-sentence="first">IntelliPupil Microvision Artificial Intelligence Laboratory is a research group focusing on how to utilize advanced chip technology and artificial intelligence algorithms to achieve precise machine vision functions. 'IntelliPupil' and 'Microvision' symbolize the ability to see and understand the world, which implies that we aim to equip the machine with the ability of learning from multiple modalities, under the direction of doing valuable contribution to the community and society. If you are interested in our lab, you can learn more via the following ways.</p>
  
  <p class="sentence" data-sentence="second" style="display:none;">智瞳微视人工智能实验室，乃一研修群体也。以精研前沿芯片技艺与人工智能算法为要务，致力于构筑精准之机器视觉系统。所谓“智瞳”，寓意智能洞察；“微视”，象征细致观微，二者合一，蕴含“以智能之瞳，观世界之微”的宏愿。夫观万象于毫厘，察乾坤于方寸，此乃吾等夙志。实验室志在赋予机器以多模态学习之能，使其能“听之以耳，观之以目，思之以心”，从而达成理解世界、服务人群之道。若君对斯室有意，愿与之同道，可循下方途径，探其奥妙。 </p>

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