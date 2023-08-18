<h1 align="center"> Faithful LLMs for Long-Horizon Task Planning </h1>

<div align='center'>
  <style="font-size:"2"; "> ICRA 2024 </font>
</div>

<div align='center'; style="font:12px; bolder '微软雅黑';">
  ICRA 2024
</div>

<p align='center'; style="font-size:24px; "> ICRA 2024 </p>

<head>
    <title>文本样式：设置字体、颜色、大小、粗细、对齐方式、背景色、高度、文本装饰、文本行的高度</title>
    <style>
        div{
            font-family: "宋体";
            color: darkorange;
            font-size: 24px;
        }
        
        a{
            text-decoration: none;
            background-color:greenyellow;
            font-size: 30px;
            height: 60px;
        }
 
        s{
            text-decoration: none;
            background-color: lightblue;
            font-size: 30px;
            height: 60px;
        }
    </style>
</head>

<center><font face="黑体" size=6 color=red>文字居中并带颜色</font></center>

## Abstract
Recent planning methods based on LLMs typically employ the In-Context Learning paradigm. Complex long-horizon tasks require more context(including instructions and demonstrations) to guarantee generated plan can be executed. However, in such condition, LLMs may overlook(unfaithful) the rules in the given context, resulting in plans that can be invalid or even lead to dangerous actions. In this paper, we investigate the faithfulness of LLMs for complex long-horizon tasks. Inspired by human intelligence, we introduce a novel framework named DiEP. DiEP employs a language-based RNN structure to integrate task decomposition, memory management into LLM planning inference, which could effective improve the faithfulness of LLM and make planner more reliable. We conducted experiments in VirtualHome household tasks. Results show that our model significantly improves faithfulness and success rates for complex long-horizon tasks.

## Video

## Results

## Methodology

## BibTeX
