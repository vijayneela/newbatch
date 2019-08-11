# Welcome to DevOps Training.

As a begineer to the you need to create an account in AWS in order to proceed with the lab practice.

Following are the list of setups you need to perform.

## a. Create AWS Account.

### 1. You need to create an account by opening the following URL and click on "Create Free Account"

http://aws.amazon.com

![image](/uploads/353c75f031be740998c99f4bf8ff35ba/image.png)

### 2. Fill your details to create an account. Details required are Email address and your account name of your choice.

### 3. After submitting the data you will be taken to SignUp form which requires more details.
    i. Select Account Type as `Personal`
    ii. Your address and Mobile number. (Need to provide a valid mobile number, You will recive a call in further setup)

![image](/uploads/89b7267d579b2ec48737d64e649d93df/image.png)

### 4. Next you will be prompt to provide the credit card details. So proceed by providing the details
    i. Provide credit/debit card details.
    ii. Select PAN number as NO
    

![image](/uploads/62357c0caee93712d7974dc0620f6b58/image.png)

### 5. You will be redirected to your bank payment portal to provide OTP and after that select the plan as `Basic`.

### 6. Once after your account creation is completed then use the following link to open your account.

http://console.aws.amazon.com

![image](/uploads/2569bb7a610e1fd49afd54b37de5f74d/image.png)


## b. Create a server in AWS.

Choose a region of your choice. (N.Virginia, Ohio, or Oregon)

Choose a service called as `EC2` and create a Server as shown.


![image](/uploads/5ce968e9c22a29685b018392b5c85734/image.png)

![image](/uploads/720aa0db98061d10d69ee5d72adefa7d/image.png)

![image](/uploads/96da52f3964dfd8b4490203dc8ca8ebc/image.png)

![image](/uploads/57e780c32ccfe6a2f82be0e7fc5c9153/image.png)

Owner: 973714476881

Then select the AMI and click on "Launch"

![image](/uploads/787b1d027563c36c6d410992c133ef16/image.png)

Select "t2.micro" and proceed.


![image](/uploads/2d0eba6bc61849ef571e3a80605b0987/image.png)

No changes required, Just Click on "Add Storage"

![image](/uploads/f9a5253ad363d875f3612c163b8cbb32/image.png)

No changes required , Click on "Add Tags"

![image](/uploads/8143f36d2bd5bd44798d80cfa102a0d7/image.png)

Click on "Next: Configure Security Group"


![image](/uploads/98e7dc4dfd194332f2ece954c263d27f/image.png)


Finally Click on "Review and Launch" and "Launch"

![image](/uploads/7c2fd2045593377289fbdc7156a0a8a8/image.png)

Select "Proceed with out KeyPair"

Then use the Public IP of the server and connect it with Putty , Using the following credentials.

Username / Password : root / DevOps321


### 

### Install GitBash

`MAC and Linux Users can ignore this installation`

Download the GitBash from https://git-scm.com/downloads and install it with default options

Then,

Open the GitBash and run the following commands. But Mac and Linux Users can use `Terminal` to run these commands.

`$ ssh-keygen -f devops `   <- You will be asked to enter Passphrase prompt , But just hit ENTER.

`$ mv devops devops.pem `

![image](/uploads/cd693b51cc08df01d79745b1b4ab4607/image.png)

## Upload `devops.pub` file into AWS.

