# BMI Calculator Prompt
## Create a BMI Calculator
``` markdown
Write a console application, it's a BMI calculator, that takes the following inputs:
- weight in pounds
- height in meters

Calculate the BMI and get the BMI category.
Then display the result in a user-friendly format.
```



## Unit Test Prompt
``` markdown
@workspace /new 幫我建立單元測試

針對: poundsToKg, calculateBMI, getBMICategory 來進行單元測試，將這三個function 的單元測試分別放在不同的 file 裡；其他的 function 不要建立單元測試

NodeJS 請使用 Jest 來進行單元測試
Python 請使用 PyTest 來進行單元測試
CSharp 請使用 MSTest 來進行單元測試
Java 請使用 JUnit 來進行單元測試

請盡可能的產生多的測試案例，並且要包含邊界條件的測試案例

每個單元測試要獨立的 function

請確保所有的單元測試都要符合 3A 原則，不可省略
```

# WPF Async Downloader
## Explanation Prompt
``` markdown
@workspace 幫我使用簡體中文詳細說明這個專案的用途、設計與架構
```

### Flowchart Prompt
``` markdown
請幫我使用 mermaid 劃出流程圖，請用英文，並確保 mermaid 語法正確
請幫我使用 mermaid 劃出這個專案的架構圖，請用英文，並確保 mermaid 語法正確
```

### README Prompt
``` markdown
@workspace /new 幫我將這個專案的說明與架構圖新增到 README.md，並且要再加上 README 的常見內容
```

## Beautify Prompt
``` markdown
請幫我美化 WPF 應用程式，讓它看起來更好看，並且要符合 WPF 的設計規範
```

``` markdown
請幫我美化 WPF 應用程式，使用 MaterialDesignInXamlToolkit 來美化
```