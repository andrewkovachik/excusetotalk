<head>
    <meta charset="UTF-8">
    <title>
        Green Audio Player
    </title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" type="text/css" href="green-audio-player.css">
    <style>
        html, body { height: 100%; }
        .ready-player-raven {
            margin: 24px 0;
        }
    </style>
</head>


# Excuse to Talk


## What is an Excuse to Talk
An excuse to talk is ran by two friends, Andrew and Jared, and exists purely as a reason for them to have conversations. Feel free to listen along to their random ramblings.

### Episode 0

In an attempt to learn about recording audio and putting it on a website, Andrew recorded his friends while talking about a poem by Edgar Allen Poe, The Raven. As this was a trial to figure out all the different components of recording and uploading the audio quality was not perfect and on occassions maxed out the recorder.

<div class="ready-player-raven player-with-download">
    <audio crossorigin>
        <source src="edgarallenpoe.mp3" type="audio/mpeg">
    </audio>
</div>

<script src="green-audio-player.js">
</script>
<script>
    document.addEventListener('DOMContentLoaded', function() {
        GreenAudioPlayer.init({
            selector: '.player',
            stopOthersOnPlay: true
        });

        GreenAudioPlayer.init({
            selector: '.player-with-download',
            stopOthersOnPlay: true,
            showDownloadButton: true,
            enableKeystrokes: true
        });

    });
</script>
