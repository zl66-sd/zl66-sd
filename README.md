<!文档类型html >
<超文本标记语言>
<头>
    <标题>九九乘法表</标题>
</头>
<身体>

<桌子边界="1" 身份证明（identification）="乘法表"></桌子>

<脚本>
    让 桌子=文档。getElementById('乘法表');
    为(让 我 = 1；我< =9；i++) {) {
let row = document . createelement(' tr ')；let row = document.createElement('tr');
for(设j = 1；j < = I；j++) {for(let j = 1; j <= i; j++) {
let cell = document . createelement(' TD ')；let cell = document.createElement('td');
cell . text content = `$ { j } * $ { I } = $ { I * j }`；textContent = `${j} * ${i} = ${i * j}`;
row.appendChild(单元格)；appendChild(cell);
        }
table . appendchild(row)；appendChild(row);
    }
</脚本>

</</body >>
</</html >>
