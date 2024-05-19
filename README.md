# Hadoop and Spark implementation with Google Cloud Plataform Dataproc
<p align="center">
  <img src="https://blogs.perficient.com/files/2014/06/elephant_rgb-TRANS_sm-300x214.png" height="75">
  <img src="https://www.databricks.com/wp-content/uploads/2019/02/spark-white.png" height="75">
  &nbsp;&nbsp;
  <img src="https://avatars.githubusercontent.com/u/59933973?s=280&v=4" height="75">
</p>

Note: This repository is associated with a challenge on the Digital Innovation One platform.

### Challenge Steps

1. Create a bucket in Cloud Storage.
2. Update the file `contador.py` with the name of the created Bucket on the lines containing `{YOUR_BUCKET}`.
3. Upload the files `contador.py` and `livro.txt` to the created bucket (instructions below).
    - [Uploading Objects - Cloud Storage Documentation](https://cloud.google.com/storage/docs/uploading-objects)

4. Use the code in a Dataproc cluster, running a PySpark Job calling `gs://{YOUR_BUCKET}/contador.py`.
5. The Job will generate a folder in the bucket called `resultado`. Inside this folder, the file `part-00000` will contain the list of words and how many times each is repeated throughout the book.

### Result Delivery

1. Create a repository on GitHub.
2. Create a file called `resultado.txt`. Inside this file, put the top 10 words most used in the book, according to the Job result.
3. Insert the files `resultado.txt` and `part-00000` into the repository and inform on the Digital Innovation One platform.
