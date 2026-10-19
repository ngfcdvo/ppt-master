<!-- ppt-master-schema: spec-lock/v1 -->
# Execution Lock

## canvas
- viewBox: 0 0 1280 720
- format: PPT 16:9

## communication
- audience: 儿科急诊、病房医师与规培进修医师，具备基本急救技能，需要可执行的床旁判断路径
- objective: 讲清儿童急性呼吸困难从定义、机制、病因、分度到四步诊断与治疗原则的完整思路，使听众能在床旁识别危重、定位病因并先救命后治病
- core_message: 先以客观体征和 ABCDE 判危重并先救命，再用四步法定位病因，尤其不能漏掉“慢、浅、弱”的缓慢型呼吸障碍
- consumption_mode: text

## mode
- mode: instructional

## visual_style
- visual_style: editorial

## colors
- bg: #FBF9F4
- secondary_bg: #F0EBE0
- surface: #F5F1E8
- primary: #123A46
- accent: #B3402F
- secondary_accent: #6E8A8F
- text: #1E2A2C
- grid: #D5CCB9
- muted_text: #5B6A6B

## typography
- font_family: "Segoe UI", "Microsoft YaHei", sans-serif
- title_family: Georgia, SimSun, "Times New Roman", serif
- body_family: "Segoe UI", "Microsoft YaHei", sans-serif
- body: 20
- title: 36
- subtitle: 28
- annotation: 16
- footnote: 16
- table_header: 18
- lead: 24
- cover_title: 64

## icons
- library: tabler-outline
- stroke_width: 2
- inventory: stethoscope, clipboard-text, list-check, alert-triangle, activity, lungs, heart, flask, droplet, brain, wind, route, first-aid-kit, clock, arrows-split

## page_rhythm
- P01: anchor
- P02: dense
- P03: breathing
- P04: dense
- P05: anchor
- P06: dense
- P07: anchor
- P08: dense
- P09: dense
- P10: dense
- P11: dense
- P12: anchor
- P13: dense
- P14: dense
- P15: breathing
- P16: dense
- P17: dense
- P18: anchor
- P19: dense
- P20: dense
- P21: anchor

## pptx_structure
- mode: flat

## forbidden
- `mask`, `<style>`, `class`, external CSS, `<foreignObject>`, `textPath`, `@font-face`, `<animate*>`, `<set>`, `<script>` / event attributes, `<iframe>`
- HTML named entities in text; write typography as raw Unicode and escape XML reserved characters
