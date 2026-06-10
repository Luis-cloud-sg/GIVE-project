<h1 align="center">Feedback World Model Enables<br />Precise Guidance of Diffusion Policy</h1>

<p align="center">
  <a href="https://arxiv.org/abs/2605.15705"><img src="https://img.shields.io/badge/arXiv-2605.15705-b31b1b?logo=arxiv&logoColor=white" alt="arXiv" /></a>
  <a href="https://arxiv.org/pdf/2605.15705"><img src="https://img.shields.io/badge/Paper-PDF-d32f2f?logo=adobeacrobatreader&logoColor=white" alt="Paper PDF" /></a>
  <a href="https://lorenzo-0-0.github.io/Feedback_World_Model/"><img src="https://img.shields.io/badge/Project_Page-Live-2ea44f?logo=googlechrome&logoColor=white" alt="Project Page" /></a>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=Lorenzo-0-0.Feedback_World_Model&left_text=Visitors&right_color=blueviolet" alt="Visitors" />
</p>

<p align="center">
  <a href="https://openreview.net/profile?id=~Pengfei_Liu21" target="_blank" rel="noopener"><strong>Pengfei Liu</strong></a><sup>1,*</sup> &nbsp;&nbsp;
  <a href="https://reagan1311.github.io/" target="_blank" rel="noopener"><strong>Gen Li</strong></a><sup>1,*</sup> &nbsp;&nbsp;
  <strong>Junqiao Fan</strong><sup>1</sup> &nbsp;&nbsp;
  <a href="https://ma-boyu.github.io/" target="_blank" rel="noopener"><strong>Boyu Ma</strong></a><sup>1</sup> &nbsp;&nbsp;
  <a href="https://jiajindou.github.io/" target="_blank" rel="noopener"><strong>Jindou Jia</strong></a><sup>1</sup> &nbsp;&nbsp;
  <strong>Yang Xiao</strong><sup>1</sup> &nbsp;&nbsp;
  <a href="https://marsyang.site/"><strong>Jianfei Yang</strong></a><sup>1,†</sup>
</p>

<p align="center">
  <sup>1</sup>MARS Lab, Nanyang Technological University, Singapore
</p>

<p align="center">
  <sup>*</sup>Equal contribution &nbsp;&nbsp;&middot;&nbsp;&nbsp; <sup>†</sup>Corresponding author
</p>

<p align="center">
  <img src="./static/images/teaser.png" alt="Feedback-Guided Policy architecture" width="95%" />
</p>

<table align="center" width="90%">
  <tr>
    <td valign="top">
      <b>Abstract.</b> Human communication is inherently multimodal, where language is often accompanied by non-verbal cues such as gestures to convey intentions. However, current Vision-Language-Action (VLA) models treat robotic manipulation as a pure text-driven task, overlooking the important role of gestures in Human-Robot Interaction (HRI). This often leads to inaccurate intent grounding and unreliable manipulation when language instructions are ambiguous or underspecified.To address this challenge, we propose GIVE (<b>G</b>esture <b>I</b>ntent via <b>V</b>isual-Semantic <b>E</b>nhancement) , an effective approach that enhances pre-trained VLA models with human gesture understanding without architectural modifications. Specifically, GIVE incorporates gesture information through two complementary pathways: a visual pathway that overlays hand skeletons and fingertip rays onto robot observations for explicit object grounding, and a semantic pathway that generates high-level descriptions of human gestures and task instructions for robust intent grounding. By jointly leveraging visual and semantic guidance, GIVE enables VLA policies to better associate gestures with manipulation behaviors and adapt to dynamic interaction intents. In real-world HRI experiments, GIVE substantially outperforms the baseline, improving target object recognition accuracy by 40% and overall task success rate by 80%, while demonstrating strong robustness and generalization to unseen spatial layouts and diverse participants.
      <br /><br />
      <img src="./static/images/mars_lab_logo.png" alt="MARS Lab" width="110" align="right" />
      <b>Correspondence:</b> Jianfei Yang &lt;<a href="mailto:jianfei.yang@ntu.edu.sg">jianfei.yang@ntu.edu.sg</a>&gt;
    </td>
  </tr>
</table>
