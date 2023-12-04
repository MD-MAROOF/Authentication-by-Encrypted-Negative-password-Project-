# Authentication-by-Encrypted-Negative-password-Project-
A Project designed for secure password storage.
<br>
Author: <b>MD.MAROOF</b>

<br>
<br>
<br>

<h2> ABSTRACT </h2>
As we all know, storing password securely is a crucial concept in systems based on password authentication which is also a very popularly used authentication technique. The system proposed by us is a password authentication frame work that is designed for secure password storage and could be easily integrated into existing authentication systems. Here, first, the received plain password from a user is hashed through a cryptographic hash function (e.g., SHA-256). Then the hashed password is converted to a negative password. Finally, the negative password is encrypted into an Encrypted Negative Password (ENP) using a symmetric key algorithm (e.g., AES) & multi-iteration encryption could be employed to further improve security. The cryptographic hash function & symmetric encryption together make it difficult to crack passwords from ENP’s. Also, there are a lot more corresponding ENPs for a given plain password, which makes precomputation attacks infeasible. The ENP is the first password protection scheme that combines cryptographic hash function, negative password & symmetric key algorithm without using any other additional information except the plain password. The proposed technology for this project is Java & MYSQL. The main application of this project is to provide security for password in any application.

<h2>Required softwares for the project</h2>
1. eclipse
2. mySQL connector
3. Apache Tomcat
