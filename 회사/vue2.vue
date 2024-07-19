<!DOCTYPE html>
<html>
<head>
    <title>Vue 예제</title>
    <script src="https://cdn.jsdelivr.net/npm/vue@2.6.14"></script>
</head>
<body>
    <div id="app">
        {{ message }}
    </div>

    <script>
        var app = new Vue({
        el: '#app',
        data: {
            message: '안녕하세요!'
        }
        });
    </script>   
</body>
</html>
