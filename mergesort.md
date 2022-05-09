## [16,21,11,8,12,22] -> Merge Sort

### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

<ol>
<li>
[16,21,11] - [8,12,22]
</li>
<li>
[16,21] - [11] - [8,12] - [22]
</li>
<li>[16] - [21] - [11] - [8] - [12] - [22] 
</ol>

#### Tek eleman kalana kadar ayırdık şimdi tekrar birleştirelim.

<ol>
<li>
[16,21] - [11] - [8,12] - [22]
</li>
<li>
[11,16,21] - [8,12,22]
</li>
<li>[8,11,12,16,21,22] 
</ol>

---

### Big-O gösterimini yazınız. 
<li>O(n*(logn)) n=6</li>