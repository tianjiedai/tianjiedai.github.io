## Honors

<ul style="margin:0 0 5px;">
  <li><autocolor><strong>National Scholarship: 2022 Fall</strong></autocolor></li> 
<!--   <li><autocolor>SJTU Excellent Undergraduate: 2023 Spring</autocolor></li> -->
<!--   <li><autocolor>Shao Ch’iu Alumni Scholarship: 2021 Fall</autocolor></li> -->
<!--   <li><autocolor>Kwang-Hua Scholarship: 2020 Fall</autocolor></li> -->
<!--   <li><autocolor>SJTU Excellence Scholarship: 2023 Fall, 2022 Fall, 2021 Fall, 2020 Fall</autocolor></li> -->
<!--   <li><autocolor>SJTU Academic Progress Scholarship: 2021 Fall</autocolor></li> -->
<!--   <li><autocolor>SJTU Merit Student: 2021 Fall</autocolor></li> -->
<!--   <li><autocolor>SJTU Excellent League Member: 2024 Spring, 2022 Spring, 2020 Spring</autocolor></li> -->
<!--   <li><autocolor>Top-5 in ICCV 2023 Workshop on Computer Vision for Automated Medical Diagnosis CXR-LT Competition</autocolor></li> -->
  <li><autocolor>Finalist in 2021 Mathematical Contest in Modeling (MCM/ICM)</autocolor></li>
<!--   <li><autocolor>Second Prize of 2020 National Undergraduate Mathematics Competition</autocolor></li> -->
</ul>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>折叠示例</title>
<style>
    .arrow {
        border: solid black;
        border-width: 0 2px 2px 0; /* 尖头更小 */
        display: inline-block;
        padding: 2px; /* 尖头更小 */
        transform: rotate(45deg);
        transition: transform 0.3s ease-in-out;
    }

    .arrow.up {
        transform: rotate(-135deg);
    }

    #honorsList {
        margin: 0 0 5px;
        display: none;
    }

    button {
        background-color: transparent; /* 去除背景颜色 */
        border: none;
        cursor: pointer;
        display: flex;
        align-items: center; /* 垂直居中箭头和文字 */
        padding: 5px;
    }

    button:focus {
        outline: none;
    }

    .button-text {
        margin-left: 5px;
        font-size: 14px;
    }
</style>
</head>
<body>

<button onclick="toggleList()">
    <i class="arrow"></i>
    <span class="button-text">Click to show others</span>
</button>
<ul id="honorsList">
  <li>SJTU Excellent Undergraduate: 2023 Spring</li>
  <li>Shao Ch’iu Alumni Scholarship: 2021 Fall</li>
  <li>Kwang-Hua Scholarship: 2020 Fall</li>
  <li>SJTU Excellence Scholarship: 2023 Fall, 2022 Fall, 2021 Fall, 2020 Fall</li>
  <li>SJTU Academic Progress Scholarship: 2021 Fall</li>
  <li>SJTU Merit Student: 2021 Fall</li>
  <li>SJTU Excellent League Member: 2024 Spring, 2022 Spring, 2020 Spring</li>
  <li>Top-5 in ICCV 2023 Workshop on Computer Vision for Automated Medical Diagnosis CXR-LT Competition</li>
  <li>Second Prize of 2020 National Undergraduate Mathematics Competition</li>
</ul>

<script>
function toggleList() {
    var list = document.getElementById('honorsList');
    var arrow = document.querySelector('.arrow');
    if (list.style.display === 'none') {
        list.style.display = 'block';
        arrow.classList.add('up');
    } else {
        list.style.display = 'none';
        arrow.classList.remove('up');
    }
}
</script>

</body>
</html>
