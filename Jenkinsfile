// index.js

exports.handler = async (event) => {
    // Your Lambda function logic goes here
    const htmlContent = `
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Hello Lambda</title>
        </head>
        <body>
            <h1>Hello from Lambda!</h1>
        </body>
        </html>
    `;

    const response = {
        statusCode: 200,
        headers: {
            'Content-Type': 'text/html',
        },
        body: htmlContent,
    };

    return response;
};
