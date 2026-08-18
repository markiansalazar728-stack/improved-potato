
    <section class="media-section">
        <h3>Photos</h3>
        <div class="media-grid">
            <div class="content">
                <h4>TOKYO</h4>
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS1CGif0-dasbC5O_09q1C1MN7Kr-ZLs-i0-qScuH-B2FtLptgl5Jj39Q4&s=10" alt="Photo 1">
            </div>
            <div class="content">
                <h4>SWITZERLAND</h4>
                <img src="https://media.bookmundi.com/tour/highlights-of-switzerland-in-eleven-days-520313-1594020708.jpg?format=auto&quality=60&width=1772" alt="Photo 2">
            </div>
            <div class="content">
                <h4>NETHERLANDS</h4>
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSwfozeiLD--7oEj43jJdZrNWkt1lq1Bw-CuM6q2MT-C5ZGO9u-ku6C5OlL&s=10" alt="Photo 3">
            </div>
            <div class="content">
                <h4>BATANES</h4>
                <img src="https://upd.edu.ph/wp-content/uploads/2023/07/Batanes-1-1536x1023.jpg" alt="Photo 4">
            </div>
            <div class="content">
                <h4>KOREA</h4>
                <img src="https://i.natgeofe.com/n/0f550dab-11fc-460e-a39b-030b6e5cbf06/practicalguide.jpg" alt="Photo 5">
            </div>
        </div>
    </section>

    <section class="media-section">
        <h3>Audio</h3>
        <div class="media-grid">
            <div class="content">
                <h4>Audio 1</h4>
                <p>🎵Saksi Ang Langit 
                -December Avenue</p>
                <audio controls>
                    <source src="file:///storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/Sample project - Acme/Saksi Ang Langitt.mp4" type="audio/mp4">
                </audio>
            </div>
            <div class="content">
                <h>🎵SUPER FAR 
                - LANY</h4>
                <audio controls>
                    <source src="file:///storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/Sample project - Acme/Super Far.mp4" type="audio/mp4">
                </audio>
            </div>
            <div class="content">
                <h4>Audio 3</h4>
                <p>🎵Ikot-Over October</p>
                <audio controls>
                    <source src="file:///storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/Sample project - Acme/Ikot.mp4" type="audio/mp4">
                </audio>
            </div>
            <div class="content">
                <h4>Audio 4</h4>
                <p>🎵Heaven knows 
               - Skate Avenue</p>
                <audio controls>
                    <source src="file:///storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/Sample project - Acme/Heaven Knows.mp4" type="audio/mp4">
                </audio>
            </div>
            <div class="content">
                <h4>Audio 5</h4>
                <p>🎵Bakit Ganito
                 - Ylona Garcia</p>
                <audio controls>
                    <source src="file:///storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/Sample project - Acme/Falling For U Agian.mp4" type="audio/mp4">
                </audio>
            </div>
        </div>
    </section>

    <section class="media-section">
        <h3>Favorite Video Clips</h3>
        <div class="media-grid">
            <div class="content">
                <h4>Video 1</h4>
                <p>Falling For U Again</p>
                <video controls>
                    <source src="file:///storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/Sample project - Acme/Falling For U Again.mp4" type="video/mp4">
                </video>
            </div>
            <div class="content">
            
                <h4>Video 2</h4>
                <p>Never Fall In Love</p>
                <video controls>
                    <source src="file:///storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/Sample project - Acme/I Never Fall In love.mp4" type="video/mp4">
                </video>
            </div>
            <div class="content">
                <h4>Video 3</h4>
                <p>Lazy Song</p>
                <video controls>
                    <source src="file:///storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/Sample project - Acme/Lazy Song.mp4"type="video/mp4"
                </video>
            </div>
            <div class="content">
                <h4>Video 4</h4>
                <p> Bakit Ganito</p>
                <video controls>
                    <source src= "file:///storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/Sample project - Acme/Falling For U Agian.mp4"type="video/mp4">
                </video>
            </div>
            <div class="content">
                <h4>Video 5</h4>
                <p>Tell Me Why</p>
                <video controls>
                    <source src="file:///storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/Sample project - Acme/Tell Me Why.mp4"type="video/mp4">
                </video>
            </div>
        </div>
    </section>
</body>
</html>
body{
    font-family: sans-serif;
    margin: 20px;
    background: white;
}

h2{
    text-align: center;
    font-family: l;
    margin-bottom: 20px;
}

.media-section {
    margin: 30px 0;
}

.media-section h3 {
    margin-bottom: 15px;
    color: #333;
}

.media-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    align-items: flex-start;
    background-color:#7dd7a7;
    border: 5px solid black;
    border-radius: 20px;
    padding: 30px;
    box-sizing: border-box;
}

.content{
    background-color: transparent;
    padding: 15px;
    border-radius: 20px;
    border: none;
    box-sizing: border-box;
    min-height: 220px;
    width: 220px;
    display: inline-block;
    vertical-align: top;
    margin: 0;
    text-align: center;
}

.content h4 {
    margin-top: 0;
    color: rgb(14, 3, 3);
    text-align: center;
}

.content img,
.content video,
.content audio {
    width: 100%;
    border: 5px solid black;
    border-radius: 10px;
    display: block;
    margin: 20px auto 0;
    object-fit: cover;
}

.content img {
    height: 180px;
}

.content video {
    background: #000;
    min-height: 180px;
}

.content audio {
    min-height: 50px;
}
