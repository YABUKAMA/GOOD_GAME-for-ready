<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ファイルを自動でまとめるシステム</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 20px;
  }

  h1 {
    color: #333;
    text-align: center;
  }

  #fileInput {
    display: none;
  }

  .button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #4CAF50;
    color: white;
    text-align: center;
    text-decoration: none;
    font-size: 16px;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
  }

  .button:hover {
    background-color: #45a049;
  }

  #result {
    margin-top: 20px;
    padding: 10px;
    background-color: white;
    border: 1px solid #ddd;
    border-radius: 5px;
  }
</style>
</head>
<body>
  <h1>ファイルを自動でまとめるシステム</h1>
  <label for="fileInput" class="button">ファイルを選択</label>
  <input type="file" id="fileInput" multiple>
  <button onclick="combineFiles()" class="button">ファイルをまとめる</button>
  <div id="result"></div>

  <script>
    function combineFiles() {
      const fileInput = document.getElementById('fileInput');
      const files = fileInput.files;
      const resultDiv = document.getElementById('result');
      const combinedContent = [];

      // ファイルの内容を読み込み、結合する
      for (let i = 0; i < files.length; i++) {
        const file = files[i];
        const reader = new FileReader();
        reader.onload = function(event) {
          combinedContent.push(event.target.result);
          if (combinedContent.length === files.length) {
            // 全てのファイルの読み込みが完了したら、結果を表示する
            resultDiv.innerText = combinedContent.join('\n');
          }
        };
        reader.readAsText(file);
      }
    }
  </script>
</body>
</html>
