# File-Input-Box

<input>
If you want to allow users to upload a file (for example an image, video, mp3, or a PDF), you will need to use a file input box.
type="file"
This type of input creates a box that looks like a text input followed by a browse button. When the user clicks on the browse button, a window opens up that allows them to select a file from their computer to be uploaded to the website.

<form action="http://www.example.com/upload.php" method="post">
  <p>Upload your song in MP3 format:</p>
  <input type="file" name="user-song" /><br />
  <input type="submit" value="Upload" />
</form>
