## これはテスト用のあれです
## 追加しました

バグコードの例

    void bug_code()
    {
        int *a = (int *)malloc(sizeof(int));
        if (a == NULL) {
            return;
        }
    
        *a = rand();
        if (*a > 10) {
            return;
        }
    
        free(a);
    }



