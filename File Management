## 檔案IO:
with open('demo.py', 'r', encoding='UTF-8') as file:
    for line in file:
        print(line, end='')

with之後的運算式傳回的物件，可以使用as指定給變數來參考，在上面的例子中，file所參考到的物件，最後會被自動關閉，即使在with as的區塊中發生了例外，最後一定會關閉file所參考的物件。

實際上，只要物件支援環境管理協定（Context Management Protocol），就可以使用with as語句。支援環境管理協定的物件，必須實作__enter__()與__exit__()兩個方法，這樣的物件稱之為環境管理員（Context Manager）。



__file__:
module本身的位置

複製資料夾
shutil.copytree

複製文件


列出資料夾全部檔案和資料夾，可以搭配os.path.isfile 與 os.path.isdir 來判斷該項目是普通檔案還是目錄。
for path in os.listdir(folder):

pathlib
