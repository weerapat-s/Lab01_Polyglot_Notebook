# การเริ่มใช้งาน Polyglot (.NET Interactive) 

1. ใน vscode ให้กด Ctrl+Shift+P (Windows, Linux) หรือ Cmd+Shift+P (macOS) เพื่อเปิด command pallette หรือสามารถเรียกจากเมนู View -> Command Palette...
   
![alt text](./Pictures/image-05.png)

2. พิมพ์ `polyglot new` ลงในช่องคำสั่ง ระวังอย่าลบเครื่องหมาย `>` ที่ด้านหน้า

![alt text](./Pictures/image-06.png)

3. คลิกเลือกที่ `Polyglot Notebook: Create new blank notebook`


 ![alt text](./Pictures/image-07.png)

4. คลิกเลือกภาษา `C#`

![alt text](./Pictures/image-08.png)

Extension ของ vscode จะสร้างไฟล์ notebook ขึ้นมา โดยมีภาษาเริ่มต้นเป็นภาษา C# 

![alt text](./Pictures/image-09.png)


เราสามารถเลือกภาษาได้ในตอนเริ่มสร้าง notebook

เราสามารถระบุภาษาที่เขียนได้โดยใช้ magic command (จะยกตัวอย่างในข้อต่อไป)


### Cell สำหรับ Notebook

เมื่อสร้าง notebook เราสามารถเพิ่ม cell เพื่อที่จะบรรจุเนื้อหาสำหรับ notebook ได้ โดยเบื้องต้นจะกำหนดได้ 2 รูปแบบคือ ภาษาโปรแกรม และ markdown (ในลักษณะเดียวกับ github markdown)

![alt text](./Pictures/image-10.png)


### การเลือก Kernel

ในการใช้งาน cell จะต้องเลือก kernel เพื่อที่จะให้ language services สามารถทำงานได้อย่างถูกต้อง โดยแต่ละ kernel ที่ติดตั้งจะรองรับภาษาที่แตกต่างกันไป

![alt text](./Pictures/image-11.png)


### การเลือก ภาษาสำหรับ cell

ขั้นตอนต่อไปคือการเลือกภาษาที่จะเขียนใน cell ซึ่ง polyglot มีให้เลือกหลายภาษาด้วยกัน 

อย่างไรก็ตาม  เราสามารถเขียนหลายภาษาลงใน cell เดียวกัน โดยต้องระบุชื่อของภาษาด้วย magic command 

![alt text](./Pictures/image-12.png)
