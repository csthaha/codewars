### 有一段字符
- 如果字符超过 140 字，返回 false
- 如果是 空字符串，返回 false
- 所有字符以 # 号开始
- 每个单词首字母大写

- 将单词字符串， 变成单词数组 split(' ')
- 数组里每个元素都是单词，首字母要大写 map 遍历每个元素, 使用箭头函数
- 每个单词 charAt(0) 第一个字符 toUpperCase()
- 除第一个字符后 ，其余的呢？ slice(1)

how.slice(1)  //ow

split(' ') 字符串拆分为 数组
map 遍历每一项 （映射）

"How are you".split(' ').map((w) => {
    return w.charAt(0).toUpperCase() + w.slice(1)
})