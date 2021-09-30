# DFS-dan-BFS

![soal BFS DFS](https://user-images.githubusercontent.com/73216938/135390047-ed85760c-4bf6-4314-a8fd-2cae4f068598.jpeg)

## **Penjelasan DFS**

Lines 1-12 : setiap node diilustasikan menggunakan adjacency list dimana ini adalah sebuah cara yang mudah dilakukan di phyton menggunakan data structure. Dimana setiap vertex memiliki list dari node yang bersebelahan

Line 15 : variabel visited dingunakan untuk melacak setiap node yang sudah dilewati 

Line 25: dfs function dipanggil dimana didalamnya 

Lines 17-22: dfs mengikuti algoritma yang sudah dibuat. Pertama adalah mengecek apakah sebuah node sudah pernah dilewati, jika true maka pada node tersebut ditambahkan visited set. Lalu pada setiap node yang bersebelahan dengan node tersebut, lalu dfs function dipanggil lagi. Setelah semua node sudah dilewati maka function akan direturn.

## **Penjelasan BFS**

Lines 1-12 : setiap node diilustasikan menggunakan adjacency list dimana ini adalah sebuah cara yang mudah dilakukan di phyton menggunakan data structure. Dimana setiap vertex memiliki list dari node yang bersebelahan

Line 14 : visited adalah sebuah list yang digunakan untuk melacak setiap node yang sudah dilewati

Line 15 : queue adalah sebuah list yang digunakan untuk melacak node yang ada dalam queue (antrian)

Line 31 : argumen dari fungsi bfs adalah visited list, graph dalam bemtuk dictionary dan starting nodenya adalah 1

Lines 17-28 : algoritma bfs dijalankan

algoritma tersebut memeriksa dan menambah starting node ke dalam visited list and queue(antrian). Lalu selama queue mengandung elemen didalamnya, maka algoritma tersebut tetap mengambil node dari queue, menambahkan node yang bersebelahan dari node tersebut kedalam queue jika node yang bersebelahan tersebut belum dilewati sebelumnya, dan menandai node itu sebagai visited node(sudah dilewati)

algoritma ini terus berjalan sampai antrian atau queue sudah kosong
