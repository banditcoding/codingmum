# CODING MUM

| [Home][0] | [Lesson 01][1] | [Lesson 02][2] | [Lesson 03][3] | [Lesson 04][4] | [Lesson 05][5] | [Lesson 06][6] | [Lesson 07][7] | [Presentation][8] |
|:---------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------------:|:--------------:|:-----------------:|

---

### LESSON 04: INTRO TO FRAMEWORK

---

### Objectives
1. Peserta mengetahui framework sebagai alat bantu pemercepat pembuatan website.
2. Peserta mampu membangun website menggunakan framework Bootstrap.

---

### Material

#### 1. Preparation
* Download Bootstrap from http://getbootstrap.com/css/#grid
* Find and copy file `bootstrap.css` into your project's folder.

#### 2. Container and Row sebagai parent dari kolom-kolom.
* Bootstrap 1 Kolom
  ```html
  <div class="container">
    <div class="row">
      <div class="col-xs-12">
        Satu kolom
      </div>
    </div>
  </div>
  ```
* Bootstrap 2 Kolom
  ```html
  <div class="container">
    <div class="row">
      <div class="col-xs-6">
        Kolom 1
      </div>
      <div class="col-xs-6">
        Kolom 2
      </div>
    </div>
  </div>
  ```
* Bootstrap 3 Kolom
  ```html
  <div class="container">
    <div class="row">
      <div class="col-xs-4">
        Kolom 1
      </div>
      <div class="col-xs-4">
        Kolom 2
      </div>
      <div class="col-xs-4">
        Kolom 3
      </div>
    </div>
  </div>
  ```
* Bootstrap 3 Kolom Kompleks
  ```html
  <div class="container">
      <div class="row">
          <div class="col-xs-4 merah">
              <div class="anak1">
                  <h4>Anak 1</h4>
                  <p>Ini paragraf Ini paragraf Ini paragraf</p>
              </div>
          </div>
          <div class="col-xs-4 orange">
              <div class="row">
                  <div class="col-xs-12 orange">Cucu 1</div>
                  <div class="col-xs-12 ungu">Cucu 2</div>
              </div>
          </div>
          <div class="col-xs-4 hijau">
            <div class="row">
                <div class="col-xs-12 ungu">Cucu 1</div>
                <div class="col-xs-12 orange">
                    <div class="row">
                       <div class="col-xs-6 hijau">Cicit 1</div>
                       <div class="col-xs-6 merah">Cicit 2</div>
                    </div>
                </div>
            </div>
          </div>
      </div>
  </div>
  ```

#### 2. CSS pembantu
* CSS `style.css`
  ```css
  .merah {
      background-color: red;
  }
  .ungu {
      background-color: purple;
  }
  .hijau {
      background-color: green;
  }
  .orange {
      background-color: orange;
  }
  .hitam {
      background-color: black;
  }
  .anak1 {
      margin-left: 20px;
  }
  ```
---

### File
[Download file for this lesson: lesson-04.zip](files/lesson-04.zip)

---

### Exercises
1. Peserta membuat 4 kolom menggunakan Bootstrap.

---

### Feedback
1. Apa yang menjadi bottleneck dari **lesson 04** ini?
2. Apa yang sebaiknya ditambah dan ditiadakan dari materi **lesson 04** ini?

---

### References
1. [Bootstrap Official](http://getbootstrap.com/ "Bootstrap Official")
2. [Front-End Web UI Frameworks and Tools](https://www.coursera.org/learn/web-frameworks "Front-End Web UI Frameworks and Tools")
2. [Introduction to Bootstrap](https://www.edx.org/course/introduction-bootstrap-tutorial-microsoft-dev203x-2 "Introduction to Bootstrap")

---

| [Home][0] | [Lesson 01][1] | [Lesson 02][2] | [Lesson 03][3] | [Lesson 04][4] | [Lesson 05][5] | [Lesson 06][6] | [Lesson 07][7] | [Presentation][8] |
|:---------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------------:|:--------------:|:-----------------:|

[0]: README.md "Home"
[1]: lesson-01.md "Website Development Introduction"
[2]: lesson-02.md "HTML and CSS Basic"
[3]: lesson-03.md "Website Structure"
[4]: lesson-04.md "Framework Introduction"
[5]: lesson-05.md "Framework (Continued))"
[6]: lesson-06.md "Personal Project"
[7]: lesson-07.md "Domain, Hosting dan GitHub"
[8]: lesson-08.md "Presentation"
