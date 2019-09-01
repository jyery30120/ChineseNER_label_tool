# ChineseNER_label_tool


就 需要用就寫寫 我自己的標註工具

分為['B-LOC','I-LOC','B-PER','I-PER','B-ORG','I-ORG']

LOC：地點

PER：人名

ORG：組織

#

這裡就填自己要的 基本手動填

```yo
LOC_list = ['大理']  #地名  
PER_list = ['蕭峰','段正淳','阮星竹','褚萬里','段延慶','南海鱷神','范驊','巴天石','朱丹臣','華赫艮','褚兄弟','木婉清','阿朱']  #人名  
ORG_list = ['神農幫']  #組織名
```

## 小小成果

段 o  
姓 o  
是 o  
大 B-LOC  
理 I-LOC  
國 o  
的 o  
國 o  
姓 o  
， o  
大 B-LOC  
理 I-LOC  
境 o  
內 o  
姓 o  
段 o  
的 o  
成 o  
千 o  
成 o  
萬 o  
， o  
左 B-PER  
子 I-PER  
穆 I-PER  
當 o  
時 o  
聽 o  
了 o  
也 o  
不 o  
以 o  
為 o  
意 o  

然後就...找個模型訓練吧
