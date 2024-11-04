<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SafeLink</title>
    <script>
        function openMultipleLinks() {
            const urls = [
                "https://example1.com",
                "https://example2.com",
                "https://example3.com",
                "https://example4.com",
                "https://example5.com"
            ];
            urls.forEach(url => window.open(url, '_blank'));
        }
    </script>
</head>
<body onload="openMultipleLinks()">
    <h1>Mohon tunggu, link sedang dibuka...</h1>
</body>
</html>
