# ExamBuilder

<img src='/logo.png' alt='logo' width='160' height='160'/>
<p>Build Knowledge, Master Topics: Interactive Learning with Smart Questionnaires<p>

[![Open issues][issues-badge]][issues-url]
![HTML][html-badge]
![css3][css3-badge]
![TypeScript][typescript-badge]
![Rsbuild][rust-badge]

## Description

ExamBuilder is a web application developed using React and TypeScript, designed to enable users to create, modify,and delete questionnaires without requiring a server. The app leverages the browser's built-in localStorage for data persistence, making it accessible and functional across all modern browsers.

Users can either fill out a form or input a JSON object to construct their questionnaires. Ideal as a study tool or for educators preparing classroom assessments.

## Features

* **Exam Creation:** Easily create new exams with questions, answers, options, and description.
* **Question Types:**  Supports multiple-choice questions.
* **Exam Management:** View, edit, and delete existing exams.
* **Responsive Design:**  Adaptable to various screen sizes (mobile, tablet, laptop, and larger screens).

### JSON Format

```json
{"title":"","questionnarire":[{"question": "","options": ["", "", ""],"answer": "Number in options range (start at 0)","description": ""},...]}
```

## License

This project is licensed under the [MIT License](LICENSE).

[issues-badge]: https://img.shields.io/github/issues/TinyCreator/ExamBuilder-web-app?style=for-the-badge

[issues-url]: https://github.com/TinyCreator/ExamBuilder-web-app/issues

[typescript-badge]: https://img.shields.io/badge/typescript-typescript?style=for-the-badge&logo=typescript&logoColor=%23FFFFFF&logoSize=auto&color=blue

[css3-badge]: https://img.shields.io/badge/css-css3?style=for-the-badge&logo=css&logoColor=%23FFFFFF&logoSize=auto&color=purple

[html-badge]: https://img.shields.io/badge/html-html?style=for-the-badge&logo=html5&logoColor=%23FFFFFF&logoSize=auto&color=orange

[rust-badge]: https://img.shields.io/badge/rsbuild-rsbuild?style=for-the-badge&logo=rust&logoColor=%23FFFFFF&logoSize=auto&color=grey
