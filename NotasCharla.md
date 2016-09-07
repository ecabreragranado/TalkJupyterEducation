# Charla Jupyter -Docencia TU-Dresden

## Estructura


1. Motivation (check Elena's talk -pechakucha)

  1.1 New ways of teaching: flipped classrooms, BYD, MOOCs -> Computer assisted learning.
  1.2 => New problems to be managed by the teacher:
        1.2.1 Installation problems 
        1.2.2 Different formats depending on the student
        1.2.3 Powerpoint presentations are too static
  1.3 Objective: Provide an optimum environment to be used in scientific courses to focus on learning.
  1.4 Features:
      1.4.1 No installation -> Online Environment.
      1.4.2 Full control of the software installed by the teacher.
      1.4.3 Easy access by the students -> Web Browser
      1.4.4 Flexible -> Multimedia integration, text, code...
      1.4.5 Collaboration between students to allow work on small groups.
      1.4.6 Open Source (?) Just a preference.



2. Jupyter (Ju-lia, Py-thon, R) Notebook. 

    2.1 What is it?
        2.1.1. Web interface to different programming languages (originally Python).
        2.1.2. Allow rich text (markdown), code, pictures, videos... to be embedded in the document.
        2.1.3 Different kernels (programming languages): Python, Octave, Julia, R, bash, haskell, ruby, etc.
        2.1.4 Converting tool (nbconvert) to generate LaTeX, PDF, slideshows, etc.
        2.1.5 Open Source
        2.1.6 Extensions. Example: RISE (this slideshow)
NOTA: Antes de hablar de RISE hay que decir en que consiste el notebook: celdas, etc, con un ejemplo.
    2.2 How does it works?
        2.2.1 Server - client 
        2.2.2. Jupyter Notebook is a JSON-file
    2.3 Examples of teaching resources: theory and exercises

3. Providing the multiuser environment: JupyterHub
    3.1 Features
        3.1.1 Each student runs its own server: cloud space
        3.1.2 The multiuser server (JupyterHub) runs in teachers computer (or amazon's cloud, etc)
        3.1.3 Authentication: generate unix users for each student or authenticate via OAuth: GitHub, Google.
        3.1.4 Security?. That can be an issue -> docker images
    3.2 What about setting up a course?. NbGrader
        3.3 Nbgrader manages assignment generation, release, student submission, calification and feedback
        3.4 It can run automatic tests to automate exercise correction and speed up feedback
    3.3 An example: My course on Introduction to scientific numerical tools in Optics.
    
4. This is too much for me. Any out-of-the-box solution? -> SMC
    4.1 What is SMC?
    4.2 How does it work?
    4.3 pros and cons
    
 
