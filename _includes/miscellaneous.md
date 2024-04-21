## Miscellaneous
- **🎹:** I'm a fan of _Chopin_ and also keen on _traditional compositions_. I will record a series of pieces and upload them in the future. Stay tuned!
    * Ballade No. 1 in G minor, Op. 23
    * Waltz in D-flat major, Op. 64, No. 1
    * Grande Valse in A-flat major, Op. 42
    * Nocturne in E-flat major, Op. 9, No. 2
    * The Mountain Azaleas are Blooming Brightly Red
    * Colorful Clouds Chasing the Moon

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Music Playlist Toggle Example</title>
<style>
    .icon {
        display: inline-block;
        transition: transform 0.3s ease-in-out;
        transform: rotate(0deg); /* Initial state pointing right */
    }

    .icon.up {
        transform: rotate(90deg); /* Rotates to point down */
    }

    #musicList {
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

<button onclick="toggleMusicList()">
    <span class="icon">➡️</span>
    <span class="button-text">Click to show all</span>
</button>
<ul id="musicList">
  <li><strong>Ballade No. 1 in G minor, Op. 23</strong></li> 
  <li>Waltz in D-flat major, Op. 64, No. 1</li>
  <li>Grande Valse in A-flat major, Op. 42</li>
  <li>Nocturne in E-flat major, Op. 9, No. 2</li>
  <li>The Mountain Azaleas are Blooming Brightly Red</li>
  <li>Colorful Clouds Chasing the Moon</li>
</ul>

<script>
function toggleMusicList() {
    var list = document.getElementById('musicList');
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
