# Basic HTML

เป็น โปรเจคที่แสดง HTML พื้นฐานแบ่งออกเป็น 2 HTML file ได้แก่

 1. index.html
 2. mypets.html
 


----------
## index.html 
แสดงวิธีการใช้งานภาษา HTML แบ่งออกเป็นหัวข้อย่อยดังนี้

 1. การเพิ่ม option ให้ตัวอักษร เช่น
	-	ทำตัวหนาใช้tag: b, strong
		```html
		<b>bold</b>
		<strong>storng</strong>
		```
	-	ทำตัวเอียงใช้ tag: I, emp
		```html
		<I>i</I>
		<emp>Emphasis</emp>
		```
2. การแสดง List ได้แก่
	-	List แบบเรียงลำดับใช้ tag: ol
		```html
		<ol>
			<li>order1</li>
			<li>order2</li>
		</ol>
		```
	-	List แบบไม่เรียงลำดับใช้ tag: ul
		```html
		<ul>
			<li>order A</li>
			<li>order B</li>
		</ul>
		
3. การใช้ div และ span
	- div เป็น tag ที่ใช้จัดกลุ่มของ html element 
	- span เป็น tag ที่ใช้จัดกลุ่มข้อมูลแบบ inline
	```html
		 <div style="background-color: bisque">
            <h2> Div And Span</h2>
            <p>
                Lorem ipsum dolor sit amet, <span style="color: red">consectetur</span> adipiscing elit. Cras id nisi ornare, molestie lorem pharetra, luctus augue. Aenean leo orci, facilisis id maximus a, viverra a odio. Mauris ac libero et magna blandit sodales convallis et lorem. Donec porttitor efficitur feugiat. Donec luctus malesuada nisi sit amet blandit. Vivamus id malesuada elit. Mauris auctor lorem tortor, sit amet bibendum ante rutrum quis. Sed at dignissim libero, vitae euismod risus. Aliquam in semper urna
            </p>
        </div>
4. HTML Attribue
	- ค่าที่ใส่เข้าไปใน html element เช่นตัวอย่างใน tag img คือ src และ art 
	 ```html
		 <img src="React-Logo-1.png" alt="react logo" />
----------
## mypets.html 
นำความรู้ที่ได้จาก index.html มาสร้าง html page ง่ายๆ
