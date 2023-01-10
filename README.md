# -LT-10_StringTemplate

String template adalah fitur dalam JavaScript yang memungkinkan Anda untuk membuat string dengan cara yang lebih mudah dan bersih. String template menggunakan tanda kurung kurawal (`) untuk menandai string literal dan menggunakan placeholder bernama ${expression} untuk menyisipkan nilai dari expression ke dalam string.

Contoh:

    let name = "John";
    let age = 30;

    console.log(`My name is ${name} and I am ${age} years old.`);
    // output: "My name is John and I am 30 years old."

String template juga dapat digunakan untuk menulis string multi-baris dengan cara yang lebih mudah, tanpa perlu menggunakan karakter escape (). Contoh:

    let message = `This is a
    multi-line
    string`;

    console.log(message);
    // output: "This is a
    // multi-line
    // string"

String template juga dapat digunakan untuk menyisipkan hasil evaluasi expression yang lebih kompleks ke dalam string. Contoh:

    let x = 10;
    let y = 20;

    console.log(`${x} + ${y} = ${x + y}`);
    // output: "10 + 20 = 30"

