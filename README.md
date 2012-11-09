## What happened to the code?
[Amazon Web Services](http://aws.amazon.com/) is moving code hosted at GitHub to a new
GitHub organization: <http://github.com/aws>. Nothing is lost. Only moved.

## What do I do now?
Simply update the URL of the repository's origin:

	First, change the URL of the origin:
	$ git remote set-url origin git@github.com:aws/aws-sdk-android.git

	Next, verify it worked
	$ git remote -v

	Lastly, move your local repository to the new name (without the "for")
	$ mv aws-sdk-for-android aws-sdk-android
