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
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
<style>
    .icon {
        display: inline-block;
        transition: transform 0.3s ease-in-out;
        color: black; /* 可以修改颜色 */
        font-size: 18px; /* 控制图标大小 */
        transform: rotate(0deg);
    }

    .icon.up {
        transform: rotate(180deg);
    }

    #honorsList {
        margin: 0 0 5px;
        display: none;
    }

    button {
        background-color: transparent;
        border: none;
        cursor: pointer;
        display: flex;
        align-items: center;
        padding: 5px;
        margin-top: -5px;
    }

    button:focus {
        outline: none;
    }

    .button-text {
        margin-left: 5px;
        font-size: 14px;
        color: gray;
    }
</style>
</head>
<body>

<button onclick="toggleList()">
    <i class="fas fa-sword icon"></i>
    <span class="button-text">Click to show all</span>
</button>
<ul id="honorsList">
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
    var icon = document.querySelector('.icon');
    if (list.style.display === 'none') {
        list.style.display = 'block';
        icon.classList.add('up');
    } else {
        list.style.display = 'none';
        icon.classList.remove('up');
    }
}
</script>

</body>
</html>

