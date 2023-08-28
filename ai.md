---
layout: page
title: AI in STAT 9610
nav_exclude: true
permalink: /resources/ai/
---

# AI in STAT 9610
  
AI tools like ChatGPT have taken the world by storm recently, and will accelerate data science in the coming years. On the other hand, these tools often confidently give wrong answers, and must be used with caution. For more context, students are encouraged to read [this overview of AI tools](https://www.oneusefulthing.org/p/how-to-use-ai-to-do-stuff-an-opinionated) as of summer 2023, written by Ethan Mollick of the Wharton Management Department. In STAT 9610, students are encouraged to use these tools to enhance their learning and productivity. As discussed in the [Syllabus](https://apps.wharton.upenn.edu/syllabi/202330/STAT9610001/), students may use any AI tools to complete their assignments and assessments, as long as they disclose which tools they used and how they used them.

## Instructor's philosophy on AI tools

### AI in data science

AI is in a period of rapid development, so it hard to predict what impact it will have on the field of data science. At minimum, tools like ChatGPT will be used to help data scientists troubleshoot programming errors and suggest short code snippets to carry out narrowly-defined tasks. At the other end of the spectrum, one can envision AI carrying out entire data analyses from start to finish, with minimal prompting and no coding on the part of data scientists. In the instructor's opinion, we will end up somewhere in between. AI tools will serve as increasingly capable copilots (see also GitHub Copilot, discussed below) that augment human data scientists' work. Humans will still need to know how to code, but will increasingly focus on fine-tuning and verifying the correctness of the suggestions given by AI tools. The acceleration of computer programming by AI will free up more time for human data scientists to focus on the more nuanced and context-driven aspects of their work, where human insight, creativity, and critical thinking are paramount.

### AI in data science education

For STAT 9610, the instructor plans to directly engage with this new wave of AI tools in order to prepare students for a future where such tools are a key to productivity. This consideration motivated the instructor to allow students to use any AI tools for their homework. There are many ways to leverage AI tools to further data science education. However, these AI technologies are quite new, and the instructor is not an expert in these tools. Nevertheless, the instructor will do his best to point students to the tools he thinks may be the most useful to (see the next section). He hopes that students will explore a variety of ways to augment their data analysis and their studying with AI, and that this process will help them better appreciate the strengths and weaknesses of these technologies. On the other hand, students should keep in mind that they are ultimately responsible for the quality of the work they submit for the course. If an AI tool gives the wrong answer, it is the student's responsibility to correct it. If an AI tool gives the right answer, it is the student's responsibility to understand why it is right. In short, students will be expected to use AI tools to help them learn, but not to replace their learning.

## Specific tools recommended for STAT 9610

### AI tools for programming

Broadly speaking, programming can be augmented by AI tools in three different ways: 

1. Sophisticated **"auto-complete" tools integrated into coding environments** that can suggest one or more lines of code based on what the user has already typed. Such tools are exemplified by [GitHub Copilot](https://github.com/features/copilot), which is free for students (see [these instructions](https://openaimaster.com/github-copilot-free-for-students/) for getting access). Unfortunately, RStudio is not yet equipped with GitHub Copilot, although it soon will be. It is possible to use GitHub Copilot in conjunction with other integrated development environments like Visual Studio Code, but the instructor does not encourage students to pursue this option.

2. **Tools that can generate code based on a natural language description of the task.** Such tools are exemplified by [ChatGPT](https://chat.openai.com/), the GPT-3.5 version of which is free to use. OpenAI's GPT-4 is more powerful but requires ChatGPT Plus, which costs $20/month. Students who want to access GPT-4 for free can use Bing Chat instead, which uses the same underlying model. Tools like these can be used to generate code snippets or to help debug existing code.

3. **Tools that can both generate and run code based on a natural language description of the task.** Such tools are exemplified by the ChatGPT with Code Interpreter, which is available only to ChatGPT Plus users. This powerful tool accepts data files as attachments, can write and execute Python code on the user's behalf, and has some limited ability to interpret the results the code produces and diagnose bugs if they arise. Note that STAT 9610 is based on R, not Python, so this tool will not be directly useful for the course. A version of this concept is compatible with R programming via the Noteable plugin for ChatGPT (also requiring ChatGPT plus). See [this video](https://www.youtube.com/watch?v=A1ualvzgJoo&list=PLlflyXwy4bT619mPF5UYntje_AYJkTAs5&ab_channel=ChadSkelton) for how to set up and use this tool.

The instructor has tried all three of these avenues for accelerating programming, with varying degrees of success. Sometimes these tools give the wrong answers; this occurs more frequently for mathematical tasks than for programming tasks. Prompting these tools into giving high-quality answers can be challenging. Users should be prepared to edit the code that is generated, and to debug it if it does not work as expected. Having said that, all of these tools are surprisingly powerful and very much worth engaging with. The instructor encourages students to try as many of these tools as they wish and make their own conclusions about their utility.

### AI tools for learning

AI can be used not only for programming, but also to assist with learning course material. Students can use tools like ChatGPT as personal tutors, supplementing classroom instruction and office hours. Students may start a conversation with ChatGPT using a prompt like [this one tailored for R programming help](https://chat.openai.com/share/7b81ca28-5750-49f6-8df3-4f3dcbea4e3e) or [this one tailored for statistics help](https://chat.openai.com/share/cae0d7f7-bcef-4ca1-957d-82262ee324dd) (both inspired by [a more general prompt](https://chat.openai.com/share/ec1018ec-1d86-4160-b587-354253c7d5cb) constructed by Ethan and Lilach Mollick) to have the AI walk them through a topic of their choice. Of course, the correctness of the answers given by ChatGPT is not guaranteed, and students who try this are encouraged to consult with the human teaching staff of the course to check their understanding.
