# Student-E-Commerce-API

> Short and compelling one-liner description of your project.
This is a school management project for students to buy and sell items online.
---

## 🚀 Installation & Setup

### Prerequisites

- Node.js (v18+)
- npm
- Git

### Clone the Repository

```bash
https://github.com/KazeemAkin/Student-E-Commerce-API 

### Clone the Frontend Repository
# open your code editor (VSCode)
# open terminal
# run the following
git clone git@github.com:KazeemAkin/Student-E-Commerce-API.git
cd Student-E-Commerce-API
npm install
openssl genpkey -algorithm RSA -out private.key -pkeyopt rsa_keygen_bits:4096
openssl rsa -pubout -in private.key -out public.key 

# create a file named .env on the root folder
# add the following data to it. 

###

  # URLS
  # DB VAARIABLES
  MAXIDLE_TIMES=270000
  DB_POOL_SIZE=100
  DB_NAME="StudentEcommerce"
  DB_URL=mongodb+srv://anciemtutors:a5eZU0eCVpWP9yAX@anciem.rp74bds.mongodb.net/test?retryWrites=true&w=majority
  SITE_URL=http://localhost:3000

  # SALT
  SALT=10

  # PORT
  PORT=8094

  issuer="student-ecommerce api"

  #aws 
  aws_bucket=anciem
  aws_access_key=AKIAQ2IBIUTXTR52KSNG
  aws_secret_access_key=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
  aws_region="eu-north-1"
  aws_route="student-ecommerce/"

  #stripe 
  STRIPE_PUBLIC_KEY="pk_test_51TSYEUGkZD8lzq0XfggkE2PsEHx9Q5oTZR0f8gf5WoLFoKCegZh72mCZYfHM2TulVWmG76dfn8Mz1ZR182SyGCBN00lh0ZVTS1"
  STRIPE_SECRET_KEY="sk_test_51TSYEUGkZD8lzq0X3pTkLSeZvh3sDxMo6B89EACFw0VFgfqo1KtslWK1mY8RQ9znlSfEwlWwEufEDrl8zzJjuMzU00b9XHmdB4"

  #mailgun 
  MAILGUN_API_KEY="206ba295084a25abd067a7e7c7a089ce-4293193c-f7bd1fd8"
  MAILGUN_URL="student-e-commerce.handivice.com"
  MAILGUN_EU="https://api.eu.mailgun.net"
  MAILGUN_FROM_EMAIL=akinpeludavid346@gmail.com

###

# then, on the terminal, 
# enter
npm run dev

# install mongodb 

# for MacOs
# Using Homebrew (Recommended)
# open your terminal and run the following
brew tap mongodb/brew
brew install mongodb-community@8.0
brew services start mongodb-community


# for Windows
  # Step 1: Download MongoDBOpen your browser and go to:
    # https://www.mongodb.com/try/download/community
    # Select these options:Version: 8.0 (Recommended) or 8.3
    # Platform: Windows
    # Package: MSI

    # Click Download.

  # Step 2: Install MongoDBRun the downloaded .msi file (as Administrator).
    # Click Next on the welcome screen.
    # Accept the license agreement → Next.
    # Important Setup Options:Setup Type: Choose Complete
    # Check the box: "Install MongoDB as a Service" (Recommended)
    # Check the box: "Install MongoDB Compass" ← This will install Compass together
    # Data Directory: Leave default (C:\Program Files\MongoDB\Server\8.0\data)
    # Log Directory: Leave default

    # Click Next → Install.
    # Wait for installation to complete → Click Finish.

# Alternative: Manual Start (If needed) for windows
  Open Command Prompt as Administrator and run:bash
  # Start MongoDB
  net start MongoDB
  # Stop MongoDB
  net stop MongoDB

# open database in compass
  # Go to your browser and download compass
# Verify Installation
  # Open MongoDB Compass
  # Compass will It will automatically try to connect to: mongodb://localhost:27017

