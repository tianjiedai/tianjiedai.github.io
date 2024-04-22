## Honors

<ul style="margin:0 0 5px;">
  <li><autocolor>2022 National Scholarship</autocolor></li> 
<!--   <li><autocolor>SJTU Excellent Undergraduate: 2023 Spring</autocolor></li> -->
<!--   <li><autocolor>Shao Ch’iu Alumni Scholarship: 2021 Fall</autocolor></li> -->
<!--   <li><autocolor>Kwang-Hua Scholarship: 2020 Fall</autocolor></li> -->
<!--   <li><autocolor>SJTU Excellence Scholarship: 2023 Fall, 2022 Fall, 2021 Fall, 2020 Fall</autocolor></li> -->
<!--   <li><autocolor>SJTU Academic Progress Scholarship: 2021 Fall</autocolor></li> -->
<!--   <li><autocolor>SJTU Merit Student: 2021 Fall</autocolor></li> -->
<!--   <li><autocolor>SJTU Excellent League Member: 2024 Spring, 2022 Spring, 2020 Spring</autocolor></li> -->
<!--   <li><autocolor>Top-5 in ICCV 2023 Workshop on Computer Vision for Automated Medical Diagnosis CXR-LT Competition</autocolor></li> -->
  <li><autocolor>2021 Finalist in MCM/ICM</autocolor></li>
<!--   <li><autocolor>Second Prize of 2020 National Undergraduate Mathematics Competition</autocolor></li> -->
</ul>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Toggle Example</title>
<style>
    .icon {
        display: inline-block;
        transition: transform 0.3s ease-in-out;
        transform: rotate(0deg); /* Initial state pointing right */
    }

    .icon.up {
        transform: rotate(90deg); /* Rotates to point down */
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
        margin-top: -5px; /* Adjust as needed for alignment */
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
    <span class="icon">➡️</span>
    <span class="button-text">Show all</span>
</button>
<ul id="honorsList">
       <li><autocolor>2024/2022/2020 SJTU Excellent League Member</autocolor></li> 
       <li><autocolor>2023/2022/2021/2020 SJTU Excellence Scholarship</autocolor></li>
       <li><autocolor>2023 SJTU Excellent Undergraduate</autocolor></li>
       <li><autocolor>2021 SJTU Merit Student</autocolor></li>
       <li><autocolor>2021 Shao Ch’iu Scholarship</autocolor></li>
       <li><autocolor>2021 SJTU Academic Progress Scholarship</autocolor></li> 
       <li><autocolor>2020 Kwang-Hua Scholarship</autocolor></li>
       <li><autocolor>2020 Second Prize of National Undergraduate Mathematics Competition</autocolor></li> 
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
