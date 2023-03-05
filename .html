from flask import Flask, render_template, request, redirect, url_for

app = Flask(__name__)

@app.route('/', methods=['GET', 'POST'])
def login():
    if request.method == 'POST':
        # Get the username and password from the form
        username = request.form['username']
        password = request.form['password']
        
        # Check if the username and password are valid
        if username == 'admin' and password == 'password':
            # If the credentials are valid, redirect to the home page
            return redirect(url_for('home'))
        else:
            # If the credentials are invalid, show an error message
            error = 'Invalid username or password. Please try again.'
            return render_template('login.html', error=error)
    else:
        # If the request method is GET, show the login page
        return render_template('login.html')

@app.route('/home')
def home():
    # This is the home page that is displayed after a user logs in
    return 'Welcome to the home page!'

if __name__ == '__main__':
    app.run(debug=True)