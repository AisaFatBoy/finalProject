# finalProject
DataStructure FinalProject
使用-encoding utf-8進行編譯

1/1 

AVLTree:

totalyWordsCount改為static用於計算總字數

public AVLTreeNode insert(AVLTreeNode node, String data)方法改動
重複時不加一

public void insert(String data)方法改動
每insert一個數時，totalyWordsCount加一，用於計算總字數

新增方法getTotalWordCount,用於取的樹的總字數

WordTree:

新增輸入總字數
