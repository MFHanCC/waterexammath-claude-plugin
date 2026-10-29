# WaterExamMath for Claude

Math practice for the California drinking water operator exams: Water Treatment T1-T3 and Water Distribution D1-D3.

## What it does

This plugin connects Claude to the WaterExamMath server (`https://waterexammath.com/mcp`) and adds two skills:

- `exam-coach`: practice quizzes shown one problem at a time, each graded by the server with a worked solution that cites the CA Exam Conversion Sheet; timed sets answered in blocks of 5; progress by topic; a weekly study plan.
- `getting-started`: picks your grade, saves your exam date and runs a first short quiz.

Every problem and answer is computed in code from the State Water Board's published CA Exam Conversion Sheet. It covers the math portion only, is not affiliated with the State Water Resources Control Board and does not guarantee a pass.

## How to use it

1. Install the plugin, then connect the WaterExamMath connector on the plugin's Connectors tab and sign in.
2. Ask, for example: "Quiz me on 5 D2 water math problems", "Start a timed set", "Which topics am I weakest in?" or "Make me a study plan for an exam on March 1".
3. Answer with a letter. For a timed set, answer a block at a time, like "1-A, 2-C, 3-B, 4-D, 5-A".

## What data it sends

Your answers, your chosen grade, your exam date and your study settings go to waterexammath.com so your progress is saved. Nothing else from your conversation is sent. Privacy policy: https://waterexammath.com/privacy
