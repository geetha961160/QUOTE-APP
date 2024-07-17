const quotes = [
    { text: "The only way to do great work is to love what you do.", author: "Steve Jobs" },
    { text: "Start where you are. Use what you have. Do what you can.", author: "Arthur Ashe" },
    { text: "Success is not final, failure is not fatal: It is the courage to continue that counts.", author: "Winston Churchill" },
    { text: "Believe you can and you're halfway there.", author: "Theodore Roosevelt" },
    { text: "The best way to predict the future is to create it.", author: "Abraham Lincoln" },
    { text: "It does not matter how slowly you go, as long as you do not stop.", author: "Confucius" },
    { text: "Your time is limited, so don't waste it living someone else's life.", author: "Steve Jobs" }
];

let favorites = [];

// Function to display a random quote
function displayRandomQuote() {
    const randomIndex = Math.floor(Math.random() * quotes.length);
    const quote = quotes[randomIndex];
    document.getElementById('quote-text').textContent = `"${quote.text}"`;
    document.getElementById('author').textContent = `– ${quote.author}`;
}

// Function to handle quote refresh button click
document.getElementById('refresh-button').addEventListener('click', displayRandomQuote);

// Function to handle share quote button click
document.getElementById('share-button').addEventListener('click', function() {
    const quoteText = document.getElementById('quote-text').textContent;
    const authorText = document.getElementById('author').textContent;
    const shareText = `"${quoteText}" – ${authorText}`;
    // Replace with actual share functionality (e.g., share via social media or messaging)
    alert(`Share this quote:\n${shareText}`);
});

// Function to handle favorite quote button click
document.getElementById('favorite-button').addEventListener('click', function() {
    const quoteText = document.getElementById('quote-text').textContent;
    const authorText = document.getElementById('author').textContent;
    const favoriteQuote = { text: quoteText, author: authorText };
    favorites.push(favoriteQuote);
    displayFavoriteQuotes();
});

// Function to display favorite quotes
function displayFavoriteQuotes() {
    const favoritesList = document.getElementById('favorites-list');
    favoritesList.innerHTML = '';
    favorites.forEach((favorite, index) => {
        const li = document.createElement('li');
        li.textContent = `"${favorite.text}" – ${favorite.author}`;
        favoritesList.appendChild(li);
    });
}

// Initial display of a random quote
displayRandomQuote();
