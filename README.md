<center><h1> Mesh simplification and remesh <h1></center>
<p align="right">-- GAMES101 final project</p>

<center><h2>数据结构定义</h2><center>
<h3 align="left">点/边/面的存储</h3>
<p align="left">点是 Vector3d<float><p>
<p align="left">
边是由顶点 v1 和 v2组成的结构体，构造函数初始化 v1 和 v2，重载运算符 < 用于比较边的次序，v1越小次序越靠前，v1 相同时，v2越小次序越靠前。
<p>
<p align="left">
面由顶点 v1, v2, v3 组成的类， 包含三个函数： 
</p>
<p align="left">Face::against 传入一条边找到面的下一条边</p>
<p align="left">Face::reverse 把面翻转(交换v1和v2的值)</p>
<p align="left">Face::replace 把面中的一个顶点改变</p>



<center><h2>网格简化</h2><center>





<center><h2>重新网格化</h2><center>
