<!-- ppt-master-schema: spec-lock/v1 -->
# Execution Lock

## canvas
- viewBox: 0 0 1280 720
- format: PPT 16:9

## communication
- audience: 儿科急诊、呼吸与危重症临床医师、规培医生与进修医生
- objective: 用 30 分钟教学讲解，使听众能按 ABCDE 与轻/中/重度完成快速分层，并用四步法定位病因、识别心源性及缓慢型呼吸障碍。
- core_message: 儿童急性呼吸困难先救命、后治病：用 ABCDE 分层严重度，用四步法定位病因，并警惕最易漏诊的"慢、浅、弱"型呼吸障碍。
- consumption_mode: balanced

## mode
- mode: instructional

## visual_style
- visual_style: swiss-minimal

## colors
- background: #FFFFFF
- secondary_bg: #F1F5F9
- primary: #0F3D5C
- accent: #D97706
- secondary_accent: #2A7F9E
- body_text: #1F2933

## typography
- font_family: "Microsoft YaHei", "PingFang SC", "Hiragino Sans GB", Arial, sans-serif
- title_family: "Microsoft YaHei", "PingFang SC", "Hiragino Sans GB", Arial, sans-serif
- body_family: "Microsoft YaHei", "PingFang SC", "Hiragino Sans GB", Arial, sans-serif
- body: 24
- title: 42
- subtitle: 32
- annotation: 18
- display: 64

## icons
- library: tabler-outline
- stroke_width: 2
- inventory: tabler-outline/lungs, tabler-outline/stethoscope, tabler-outline/brain, tabler-outline/activity, tabler-outline/heart, tabler-outline/alert-circle, tabler-outline/git-branch, tabler-outline/wind, tabler-outline/wave-sine, tabler-outline/arrows-split, tabler-outline/alert-triangle, tabler-outline/emergency-bed, tabler-outline/first-aid-kit, tabler-outline/target

## page_rhythm
- P01: anchor
- P02: dense
- P03: breathing
- P04: anchor
- P05: dense
- P06: anchor
- P07: dense
- P08: dense
- P09: dense
- P10: dense
- P11: anchor
- P12: anchor
- P13: anchor
- P14: anchor
- P15: anchor
- P16: dense
- P17: breathing
- P18: anchor
- P19: dense
- P20: breathing

## page_charts
- P03: agenda_list
- P05: comparison_table
- P06: circular_stages
- P07: fishbone_diagram
- P08: comparison_table
- P09: comparison_table
- P10: comparison_table
- P12: vertical_pillars
- P13: process_flow
- P16: comparison_table
- P18: process_flow
- P19: comparison_table
- P20: vertical_list

## pptx_structure
- mode: flat

## forbidden
- `mask`, `<style>`, `class`, external CSS, `<foreignObject>`, `textPath`, `@font-face`, `<animate*>`, `<set>`, `<script>` / event attributes, `<iframe>`
- HTML named entities in text; write typography as raw Unicode and escape XML reserved characters
