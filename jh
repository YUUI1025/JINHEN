<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>帅和不帅选项</title>
    <style>
        .feedback {
            font-size: 2em;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>请选择你的选项：</h1>
    <form id="choiceForm">
        <label>
            <input type="radio" name="appearance" value="handsome"> 帅
        </label>
        <label>
            <input type="radio" name="appearance" value="not_handsome"> 不帅
        </label>
    </form>
    
    <div id="feedback" class="feedback"></div>
    
    <script>
        document.getElementById('choiceForm').addEventListener('change', function() {
            const feedbackDiv = document.getElementById('feedback');
            const selectedOption = document.querySelector('input[name="appearance"]:checked');

            if (selectedOption) {
                if (selectedOption.value === 'handsome') {
                    feedbackDiv.innerHTML = '😕 错误';  // 错误的表情
                } else if (selectedOption.value === 'not_handsome') {
                    feedbackDiv.innerHTML = '✅ 正确';  // 正确的表情
              
