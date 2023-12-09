# TASK3-BHARATINTERN
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Money Tracker</title>
</head>
<body>
    <header>
        <h1>Money Tracker</h1>
    </header>

    <main>
        <section class="balance">
            <h2>Your Balance</h2>
            <p id="balance">$1,000.00</p>
        </section>

        <section class="transaction-form">
            <h2>Add a Transaction</h2>
            <form>
                <label for="description">Description:</label>
                <input type="text" id="description" name="description" required>

                <label for="amount">Amount:</label>
                <input type="number" id="amount" name="amount" required>

                <button type="submit">Add Transaction</button>
            </form>
        </section>

        <section class="transaction-history">
            <h2>Transaction History</h2>
            <ul>
                <li>Salary: +$3,000.00</li>
                <li>Groceries: -$200.00</li>
                <!-- Add more transactions dynamically -->
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Money Tracker. All rights reserved.</p>
    </footer>
</body>
</html>
</body>
</html>



body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px 0;
}

main {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.balance, .transaction-form, .transaction-history {
    margin-bottom: 20px;
}

.balance h2, .transaction-form h2, .transaction-history h2 {
    color: #333;
}

form {
    display: flex;
    flex-direction: column;
}

label {
    margin-bottom: 8px;
}

input {
    margin-bottom: 16px;
    padding: 8px;
    font-size: 16px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

button {
    padding: 10px;
    font-size: 16px;
    background-color: #4caf50;
    color: white;
    cursor: pointer;
    border: none;
    border-radius: 4px;
}

button:hover {
    background-color: #45a049;
}

ul {
    list-style: none;
    padding: 0;
}

li {
    margin-bottom: 8px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}
