from flask import Flask
app = Flask(Dhanish)

@app.route('/')
def home():
    return "Hello Dhanish from Docker + Jenkins + EC2!"

if __name__ == '__main__':
    app.run(host='0.0.0.0', port=5000)
