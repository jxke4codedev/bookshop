<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Bookshop</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
            overflow: hidden;
        }

        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 30px;
            text-align: center;
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        .nav-tabs {
            display: flex;
            background: #f8f9fa;
            border-bottom: 2px solid #dee2e6;
        }

        .nav-tab {
            flex: 1;
            padding: 15px;
            text-align: center;
            background: none;
            border: none;
            cursor: pointer;
            font-size: 16px;
            color: #495057;
            transition: all 0.3s;
        }

        .nav-tab:hover {
            background: #e9ecef;
        }

        .nav-tab.active {
            background: white;
            color: #667eea;
            font-weight: bold;
        }

        .content {
            padding: 30px;
        }

        .tab-content {
            display: none;
        }

        .tab-content.active {
            display: block;
            animation: fadeIn 0.3s;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .search-bar {
            display: flex;
            gap: 10px;
            margin-bottom: 30px;
            flex-wrap: wrap;
        }

        .search-bar input, .search-bar select {
            flex: 1;
            min-width: 200px;
            padding: 12px;
            border: 2px solid #dee2e6;
            border-radius: 8px;
            font-size: 16px;
        }

        .search-bar button {
            padding: 12px 30px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
            font-weight: bold;
            transition: transform 0.2s;
        }

        .search-bar button:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
        }

        .books-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 25px;
        }

        .book-card {
            border: 1px solid #dee2e6;
            border-radius: 12px;
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
            background: white;
        }

        .book-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.15);
        }

        .book-card img {
            width: 100%;
            height: 300px;
            object-fit: cover;
        }

        .book-info {
            padding: 15px;
        }

        .book-title {
            font-size: 18px;
            font-weight: bold;
            color: #2c3e50;
            margin-bottom: 8px;
            display: -webkit-box;
            -webkit-line-clamp: 2;
            line-clamp: 2;
            -webkit-box-orient: vertical;
            overflow: hidden;
        }

        .book-author {
            color: #7f8c8d;
            margin-bottom: 8px;
        }

        .book-price {
            color: #667eea;
            font-size: 20px;
            font-weight: bold;
            margin: 10px 0;
        }

        .book-isbn {
            font-size: 12px;
            color: #95a5a6;
            margin-bottom: 10px;
        }

        .btn {
            padding: 8px 16px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 14px;
            transition: all 0.2s;
            margin-top: 5px;
            width: 100%;
        }

        .btn-primary {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
        }

        .btn-primary:hover {
            box-shadow: 0 3px 10px rgba(102, 126, 234, 0.4);
        }

        .btn-danger {
            background: #e74c3c;
            color: white;
        }

        .btn-danger:hover {
            background: #c0392b;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            color: #2c3e50;
            font-weight: 600;
        }

        .form-group input, .form-group textarea, .form-group select {
            width: 100%;
            padding: 12px;
            border: 2px solid #dee2e6;
            border-radius: 8px;
            font-size: 16px;
        }

        .form-group textarea {
            resize: vertical;
            min-height: 100px;
        }

        .auth-container {
            max-width: 450px;
            margin: 0 auto;
        }

        .review-card {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 15px;
            border-left: 4px solid #667eea;
        }

        .review-header {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
            flex-wrap: wrap;
            gap: 10px;
        }

        .review-author {
            font-weight: bold;
            color: #667eea;
        }

        .review-rating {
            color: #f39c12;
            font-size: 18px;
        }

        .review-date {
            font-size: 12px;
            color: #95a5a6;
            margin-top: 10px;
        }

        .user-info {
            background: linear-gradient(135deg, #e8f5e9 0%, #c8e6c9 100%);
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 10px;
        }

        .alert {
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 20px;
        }

        .alert-success {
            background: #d4edda;
            color: #155724;
            border-left: 4px solid #28a745;
        }

        .alert-error {
            background: #f8d7da;
            color: #721c24;
            border-left: 4px solid #dc3545;
        }

        .alert-info {
            background: #d1ecf1;
            color: #0c5460;
            border-left: 4px solid #17a2b8;
        }

        .loading {
            text-align: center;
            padding: 40px;
            color: #7f8c8d;
        }

        .loading::after {
            content: '...';
            animation: dots 1.5s steps(4, end) infinite;
        }

        @keyframes dots {
            0%, 20% { content: '.'; }
            40% { content: '..'; }
            60%, 100% { content: '...'; }
        }

        .empty-state {
            text-align: center;
            padding: 60px 20px;
            color: #7f8c8d;
        }

        .empty-state-icon {
            font-size: 64px;
            margin-bottom: 20px;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 1.8em;
            }

            .nav-tab {
                font-size: 14px;
                padding: 12px 8px;
            }

            .books-grid {
                grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            }

            .search-bar {
                flex-direction: column;
            }

            .search-bar input, .search-bar select, .search-bar button {
                width: 100%;
            }
        }

        .stats-bar {
            display: flex;
            justify-content: space-around;
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 30px;
            flex-wrap: wrap;
            gap: 15px;
        }

        .stat-item {
            text-align: center;
        }

        .stat-number {
            font-size: 2em;
            font-weight: bold;
            color: #667eea;
        }

        .stat-label {
            color: #7f8c8d;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>📚 Online Bookshop</h1>
            <p>Discover Your Next Favorite Book</p>
        </header>

        <div class="nav-tabs">
            <button class="nav-tab active" onclick="showTab('browse')">📖 Browse</button>
            <button class="nav-tab" onclick="showTab('search')">🔍 Search</button>
            <button class="nav-tab" onclick="showTab('reviews')">⭐ Reviews</button>
            <button class="nav-tab" onclick="showTab('auth')">👤 Account</button>
        </div>

        <div class="content">
            <!-- Browse Tab -->
            <div id="browse" class="tab-content active">
                <h2>All Books in Our Collection</h2>
                <div class="stats-bar">
                    <div class="stat-item">
                        <div class="stat-number" id="totalBooks">0</div>
                        <div class="stat-label">Total Books</div>
                    </div>
                    <div class="stat-item">
                        <div class="stat-number" id="totalAuthors">0</div>
                        <div class="stat-label">Authors</div>
                    </div>
                    <div class="stat-item">
                        <div class="stat-number" id="totalReviews">0</div>
                        <div class="stat-label">Reviews</div>
                    </div>
                </div>
                <div id="allBooks" class="books-grid loading">Loading books</div>
            </div>

            <!-- Search Tab -->
            <div id="search" class="tab-content">
                <h2>🔍 Search Our Library</h2>
                <div class="alert alert-info">
                    <strong>Search Tips:</strong> Use ISBN for exact matches, Author name for all books by an author, or Title keywords to find specific books.
                </div>
                <div class="search-bar">
                    <select id="searchType">
                        <option value="isbn">📚 Search by ISBN</option>
                        <option value="author">✍️ Search by Author</option>
                        <option value="title">📖 Search by Title</option>
                    </select>
                    <input type="text" id="searchQuery" placeholder="Enter search query...">
                    <button onclick="searchBooks()">Search</button>
                </div>
                <div id="searchResults" class="books-grid"></div>
            </div>

            <!-- Reviews Tab -->
            <div id="reviews" class="tab-content">
                <h2>⭐ Book Reviews</h2>
                <div id="currentUser" class="user-info" style="display: none;">
                    <span>👤 Logged in as: <strong id="usernameDisplay"></strong></span>
                    <button class="btn btn-danger" onclick="logout()">Logout</button>
                </div>
                <div class="search-bar">
                    <input type="text" id="reviewISBN" placeholder="Enter ISBN to view/add reviews..." list="isbnList">
                    <datalist id="isbnList"></datalist>
                    <button onclick="loadReviews()">Load Reviews</button>
                </div>
                <div id="reviewsContainer"></div>
                
                <div id="addReviewForm" style="display: none; margin-top: 30px; background: #f8f9fa; padding: 20px; border-radius: 8px;">
                    <h3>✏️ Add/Update Your Review</h3>
                    <div class="form-group">
                        <label>Rating (1-5 stars)</label>
                        <select id="reviewRating">
                            <option value="5">⭐⭐⭐⭐⭐ (5 - Excellent)</option>
                            <option value="4">⭐⭐⭐⭐ (4 - Very Good)</option>
                            <option value="3">⭐⭐⭐ (3 - Good)</option>
                            <option value="2">⭐⭐ (2 - Fair)</option>
                            <option value="1">⭐ (1 - Poor)</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label>Your Review</label>
                        <textarea id="reviewComment" placeholder="Share your thoughts about this book..."></textarea>
                    </div>
                    <button class="btn btn-primary" onclick="submitReview()">📝 Submit Review</button>
                </div>
            </div>

            <!-- Auth Tab -->
            <div id="auth" class="tab-content">
                <div id="loginSection">
                    <div class="auth-container">
                        <h2>🔐 Login to Your Account</h2>
                        <div id="authMessage"></div>
                        <div class="form-group">
                            <label>Username</label>
                            <input type="text" id="loginUsername" placeholder="Enter username">
                        </div>
                        <div class="form-group">
                            <label>Password</label>
                            <input type="password" id="loginPassword" placeholder="Enter password">
                        </div>
                        <button class="btn btn-primary" onclick="login()">Login</button>
                        <p style="text-align: center; margin-top: 15px;">
                            Don't have an account? <a href="#" onclick="toggleAuth(); return false;" style="color: #667eea; font-weight: bold;">Register here</a>
                        </p>
                    </div>
                </div>

                <div id="registerSection" style="display: none;">
                    <div class="auth-container">
                        <h2>📝 Create New Account</h2>
                        <div id="registerMessage"></div>
                        <div class="form-group">
                            <label>Username</label>
                            <input type="text" id="regUsername" placeholder="Choose a username">
                        </div>
                        <div class="form-group">
                            <label>Email</label>
                            <input type="email" id="regEmail" placeholder="Enter your email">
                        </div>
                        <div class="form-group">
                            <label>Password</label>
                            <input type="password" id="regPassword" placeholder="Choose a password">
                        </div>
                        <button class="btn btn-primary" onclick="register()">Register</button>
                        <p style="text-align: center; margin-top: 15px;">
                            Already have an account? <a href="#" onclick="toggleAuth(); return false;" style="color: #667eea; font-weight: bold;">Login here</a>
                        </p>
                    </div>
                </div>

                <div id="userProfile" style="display: none;">
                    <div class="auth-container">
                        <h2>👤 Your Profile</h2>
                        <div class="user-info">
                            <div>
                                <div style="font-size: 14px; color: #7f8c8d;">Logged in as:</div>
                                <div style="font-size: 24px; font-weight: bold; color: #667eea;" id="profileUsername"></div>
                            </div>
                        </div>
                        <button class="btn btn-danger" onclick="logout()" style="margin-top: 20px;">Logout</button>
                        <div style="margin-top: 30px; padding: 20px; background: #f8f9fa; border-radius: 8px;">
                            <h3>📊 Your Activity</h3>
                            <p style="color: #7f8c8d; margin-top: 10px;">You can add, edit, and delete your book reviews from the Reviews tab.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        // Configuration
        const API_URL = 'http://localhost:3000/api';
        const DEMO_MODE = true; // Set to false to use backend server
        
        // Current user state
        let currentUser = localStorage.getItem('currentUser');
        
        // Mock data for demo mode
        let mockBooks = [
            {
                isbn: "978-0-7475-3269-9",
                title: "Harry Potter and the Philosopher's Stone",
                author: "J.K. Rowling",
                description: "The first book in the Harry Potter series. Follow Harry as he discovers his magical heritage.",
                price: 12.99,
                image: "https://images.unsplash.com/photo-1621351183012-e2f9972dd9bf?w=400&h=600&fit=crop"
            },
            {
                isbn: "978-0-544-00341-5",
                title: "The Hobbit",
                author: "J.R.R. Tolkien",
                description: "A fantasy adventure novel about Bilbo Baggins' unexpected journey.",
                price: 14.99,
                image: "https://images.unsplash.com/photo-1544947950-fa07a98d237f?w=400&h=600&fit=crop"
            },
            {
                isbn: "978-0-06-112008-4",
                title: "To Kill a Mockingbird",
                author: "Harper Lee",
                description: "A classic of modern American literature exploring racial injustice.",
                price: 10.99,
                image: "https://images.unsplash.com/photo-1543002588-bfa74002ed7e?w=400&h=600&fit=crop"
            },
            {
                isbn: "978-0-7432-7356-5",
                title: "1984",
                author: "George Orwell",
                description: "A dystopian social science fiction novel about totalitarian surveillance.",
                price: 13.99,
                image: "https://images.unsplash.com/photo-1495446815901-a7297e633e8d?w=400&h=600&fit=crop"
            },
            {
                isbn: "978-0-14-017739-8",
                title: "The Great Gatsby",
                author: "F. Scott Fitzgerald",
                description: "A novel about the American dream in the Jazz Age.",
                price: 11.99,
                image: "https://images.unsplash.com/photo-1512820790803-83ca734da794?w=400&h=600&fit=crop"
            },
            {
                isbn: "978-0-316-76948-0",
                title: "The Catcher in the Rye",
                author: "J.D. Salinger",
                description: "A story about teenage rebellion and alienation.",
                price: 12.49,
                image: "https://images.unsplash.com/photo-1524985069026-dd778a71c7b4?w=400&h=600&fit=crop"
            },
            {
                isbn: "978-0-452-28423-4",
                title: "Pride and Prejudice",
                author: "Jane Austen",
                description: "A romantic novel of manners set in Georgian England.",
                price: 9.99,
                image: "https://images.unsplash.com/photo-1550399105-c4db5fb85c18?w=400&h=600&fit=crop"
            },
            {
                isbn: "978-0-061-96436-9",
                title: "The Lord of the Rings",
                author: "J.R.R. Tolkien",
                description: "Epic fantasy trilogy about the quest to destroy the One Ring.",
                price: 24.99,
                image: "https://images.unsplash.com/photo-1589998059171-988d887df646?w=400&h=600&fit=crop"
            }
        ];

        let mockReviews = JSON.parse(localStorage.getItem('mockReviews') || '{}');
        let mockUsers = JSON.parse(localStorage.getItem('mockUsers') || '{}');

        // Initialize
        if (currentUser) {
            updateUIForLoggedInUser();
        }
        loadAllBooks();
        populateISBNList();

        // Tab navigation
        function showTab(tabName) {
            document.querySelectorAll('.tab-content').forEach(tab => {
                tab.classList.remove('active');
            });
            document.querySelectorAll('.nav-tab').forEach(tab => {
                tab.classList.remove('active');
            });
            
            document.getElementById(tabName).classList.add('active');
            event.target.classList.add('active');
        }

        // Populate ISBN datalist
        function populateISBNList() {
            const datalist = document.getElementById('isbnList');
            datalist.innerHTML = mockBooks.map(book => 
                `<option value="${book.isbn}">${book.title}</option>`
            ).join('');
        }

        // Load all books
        async function loadAllBooks() {
            const container = document.getElementById('allBooks');
            
            if (DEMO_MODE) {
                displayBooks(mockBooks, container);
                updateStats();
            } else {
                try {
                    const response = await fetch(`${API_URL}/books`);
                    const books = await response.json();
                    displayBooks(books, container);
                    updateStats();
                } catch (error) {
                    container.innerHTML = '<div class="alert alert-error">Error loading books. Make sure the server is running.</div>';
                }
            }
        }

        // Update statistics
        function updateStats() {
            document.getElementById('totalBooks').textContent = mockBooks.length;
            
            const uniqueAuthors = new Set(mockBooks.map(book => book.author));
            document.getElementById('totalAuthors').textContent = uniqueAuthors.size;
            
            const totalReviews = Object.values(mockReviews).reduce((sum, reviews) => sum + reviews.length, 0);
            document.getElementById('totalReviews').textContent = totalReviews;
        }

        // Display books
        function displayBooks(books, container) {
            if (books.length === 0) {
                container.innerHTML = `
                    <div class="empty-state">
                        <div class="empty-state-icon">📚</div>
                        <h3>No books found</h3>
                        <p>Try adjusting your search criteria</p>
                    </div>
                `;
                return;
            }

            container.innerHTML = books.map(book => `
                <div class="book-card">
                    <img src="${book.image}" alt="${book.title}" onerror="this.src='https://images.unsplash.com/photo-1495446815901-a7297e633e8d?w=400&h=600&fit=crop'">
                    <div class="book-info">
                        <div class="book-title">${book.title}</div>
                        <div class="book-author">by ${book.author}</div>
                        <p style="font-size: 14px; color: #7f8c8d; margin: 10px 0; line-height: 1.4;">${book.description}</p>
                        <div class="book-price">$${book.price.toFixed(2)}</div>
                        <div class="book-isbn">ISBN: ${book.isbn}</div>
                        <button class="btn btn-primary" onclick="viewBookReviews('${book.isbn}')">📖 View Reviews</button>
                    </div>
                </div>
            `).join('');
        }

        // Search books
        async function searchBooks() {
            const type = document.getElementById('searchType').value;
            const query = document.getElementById('searchQuery').value.trim();
            const container = document.getElementById('searchResults');

            if (!query) {
                container.innerHTML = '<div class="alert alert-error">Please enter a search query.</div>';
                return;
            }

            container.innerHTML = '<p class="loading">Searching</p>';

            if (DEMO_MODE) {
                let results = [];
                if (type === 'isbn') {
                    results = mockBooks.filter(book => book.isbn === query);
                } else if (type === 'author') {
                    results = mockBooks.filter(book => 
                        book.author.toLowerCase().includes(query.toLowerCase())
                    );
                } else if (type === 'title') {
                    results = mockBooks.filter(book => 
                        book.title.toLowerCase().includes(query.toLowerCase())
                    );
                }
                
                setTimeout(() => displayBooks(results, container), 500);
            } else {
                try {
                    const response = await fetch(`${API_URL}/books/${type}/${encodeURIComponent(query)}`);
                    const books = await response.json();
                    displayBooks(Array.isArray(books) ? books : [books], container);
                } catch (error) {
                    container.innerHTML = '<div class="alert alert-error">Error searching books.</div>';
                }
            }
        }

        // View book reviews
        function viewBookReviews(isbn) {
            document.getElementById('reviewISBN').value = isbn;
            showTab('reviews');
            const reviewTab = document.querySelectorAll('.nav-tab')[2];
            reviewTab.click();
            setTimeout(() => loadReviews(), 100);
        }

        // Load reviews
        async function loadReviews() {
            const isbn = document.getElementById('reviewISBN').value.trim();
            const container = document.getElementById('reviewsContainer');

            if (!isbn) {
                container.innerHTML = '<div class="alert alert-error">Please enter an ISBN.</div>';
                return;
            }

            const book = mockBooks.find(b => b.isbn === isbn);
            if (!book) {
                container.innerHTML = '<div class="alert alert-error">Book not found. Please enter a valid ISBN.</div>';
                return;
            }

            container.innerHTML = '<p class="loading">Loading reviews</p>';

            let reviews = [];
            if (DEMO_MODE) {
                reviews = mockReviews[isbn] || [];
            } else {
                try {
                    const response = await fetch(`${API_URL}/books/${isbn}/reviews`);
                    reviews = await response.json();
                } catch (error) {
                    container.innerHTML = '<div class="alert alert-error">Error loading reviews.</div>';
                    return;
                }
            }

            let html = `
                <div style="background: #f8f9fa; padding: 20px; border-radius: 8px; margin-bottom: 20px;">
                    <h3>Reviews for: ${book.title}</h3>
                    <p style="color: #7f8c8d; margin-top: 5px;">by ${book.author}</p>
                </div>
            `;

            if (reviews.length === 0) {
                html += `
                    <div class="empty-state">
                        <div class="empty-state-icon">⭐</div>
                        <h3>No reviews yet</h3>
                        <p>Be the first to review this book!</p>
                    </div>
                `;
            } else {
                html += reviews.map(review => `
                    <div class="review-card">
                        <div class="review-header">
                            <span class="review-author">👤 ${review.username}</span>
                            <span class="review-rating">${'⭐'.repeat(review.rating)}</span>
                        </div>
                        <p style="margin: 10px 0; line-height: 1.6;">${review.comment}</p>
                        <div class="review-date">📅 ${new Date(review.date).toLocaleDateString('en-US', { year: 'numeric', month: 'long', day: 'numeric' })}</div>
                        ${currentUser === review.username ? 
                            `<button class="btn btn-danger" onclick="deleteReview('${isbn}', '${review.username}')" style="margin-top: 10px;">🗑️ Delete My Review</button>` 
                            : ''}
                    </div>
                `).join('');
            }

            container.innerHTML = html;

            if (currentUser) {
                document.getElementById('addReviewForm').style.display = 'block';
                const existingReview = reviews.find(r => r.username === currentUser);
                if (existingReview) {
                    document.getElementById('reviewRating').value = existingReview.rating;
                    document.getElementById('reviewComment').value = existingReview.comment;
                }
            } else {
                document.getElementById('addReviewForm').style.display = 'none';
                container.innerHTML += '<div class="alert alert-error">Please login to add a review.</div>';
            }
        }

        // Submit review
        async function submitReview() {
            if (!currentUser) {
                alert('❌ Please login first!');
                showTab('auth');
                document.querySelectorAll('.nav-tab')[3].click();
                return;
            }

            const isbn = document.getElementById('reviewISBN').value.trim();
            const rating = document.getElementById('reviewRating').value;
            const comment = document.getElementById('reviewComment').value.trim();

            if (!isbn || !comment) {
                alert('❌ Please enter ISBN and comment.');
                return;
            }

            if (comment.length < 10) {
                alert('❌ Please write a more detailed review (at least 10 characters).');
                return;
            }

            const review = {
                isbn,
                username: currentUser,
                rating: parseInt(rating),
                comment,
                date: new Date().toISOString()
            };

            if (DEMO_MODE) {
                if (!mockReviews[isbn]) {
                    mockReviews[isbn] = [];
                }
                const existingIndex = mockReviews[isbn].findIndex(r => r.username === currentUser);
                if (existingIndex !== -1) {
                    mockReviews[isbn][existingIndex] = review;
                } else {
                    mockReviews[isbn].push(review);
                }
                localStorage.setItem('mockReviews', JSON.stringify(mockReviews));
                alert('✅ Review submitted successfully!');
                document.getElementById('reviewComment').value = '';
                document.getElementById('reviewRating').value = '5';
                loadReviews();
                updateStats();
            } else {
                try {
                    const response = await fetch(`${API_URL}/reviews`, {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' },
                        body: JSON.stringify(review)
                    });
                    const data = await response.json();
                    alert('✅ ' + data.message);
                    document.getElementById('reviewComment').value = '';
                    document.getElementById('reviewRating').value = '5';
                    loadReviews();
                } catch (error) {
                    alert('❌ Error submitting review.');
                }
            }
        }

        // Delete review
        async function deleteReview(isbn, username) {
            if (!confirm('⚠️ Are you sure you want to delete this review?')) {
                return;
            }

            if (DEMO_MODE) {
                if (mockReviews[isbn]) {
                    mockReviews[isbn] = mockReviews[isbn].filter(r => r.username !== username);
                    localStorage.setItem('mockReviews', JSON.stringify(mockReviews));
                }
                alert('✅ Review deleted successfully!');
                loadReviews();
                updateStats();
            } else {
                try {
                    const response = await fetch(`${API_URL}/reviews/${isbn}/${username}`, {
                        method: 'DELETE'
                    });
                    const data = await response.json();
                    alert('✅ ' + data.message);
                    loadReviews();
                } catch (error) {
                    alert('❌ Error deleting review.');
                }
            }
        }

        // Register user
        async function register() {
            const username = document.getElementById('regUsername').value.trim();
            const email = document.getElementById('regEmail').value.trim();
            const password = document.getElementById('regPassword').value;
            const messageEl = document.getElementById('registerMessage');

            if (!username || !email || !password) {
                messageEl.innerHTML = '<div class="alert alert-error">❌ Please fill all fields.</div>';
                return;
            }

            if (username.length < 3) {
                messageEl.innerHTML = '<div class="alert alert-error">❌ Username must be at least 3 characters.</div>';
                return;
            }

            if (password.length < 6) {
                messageEl.innerHTML = '<div class="alert alert-error">❌ Password must be at least 6 characters.</div>';
                return;
            }

            if (!email.includes('@')) {
                messageEl.innerHTML = '<div class="alert alert-error">❌ Please enter a valid email address.</div>';
                return;
            }

            if (DEMO_MODE) {
                if (mockUsers[username]) {
                    messageEl.innerHTML = '<div class="alert alert-error">❌ Username already exists.</div>';
                    return;
                }
                mockUsers[username] = { username, email, password };
                localStorage.setItem('mockUsers', JSON.stringify(mockUsers));
                messageEl.innerHTML = '<div class="alert alert-success">✅ Registration successful! Please login.</div>';
                setTimeout(() => {
                    toggleAuth();
                    document.getElementById('loginUsername').value = username;
                }, 1500);
            } else {
                try {
                    const response = await fetch(`${API_URL}/register`, {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' },
                        body: JSON.stringify({ username, email, password })
                    });
                    const data = await response.json();
                    if (response.ok) {
                        messageEl.innerHTML = '<div class="alert alert-success">✅ Registration successful! Please login.</div>';
                        setTimeout(() => toggleAuth(), 1500);
                    } else {
                        messageEl.innerHTML = `<div class="alert alert-error">❌ ${data.error}</div>`;
                    }
                } catch (error) {
                    messageEl.innerHTML = '<div class="alert alert-error">❌ Error registering user.</div>';
                }
            }
        }

        // Login user
        async function login() {
            const username = document.getElementById('loginUsername').value.trim();
            const password = document.getElementById('loginPassword').value;
            const messageEl = document.getElementById('authMessage');

            if (!username || !password) {
                messageEl.innerHTML = '<div class="alert alert-error">❌ Please fill all fields.</div>';
                return;
            }

            if (DEMO_MODE) {
                if (!mockUsers[username] || mockUsers[username].password !== password) {
                    messageEl.innerHTML = '<div class="alert alert-error">❌ Invalid credentials. Try registering first!</div>';
                    return;
                }
                currentUser = username;
                localStorage.setItem('currentUser', username);
                messageEl.innerHTML = '<div class="alert alert-success">✅ Login successful!</div>';
                setTimeout(() => updateUIForLoggedInUser(), 500);
            } else {
                try {
                    const response = await fetch(`${API_URL}/login`, {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' },
                        body: JSON.stringify({ username, password })
                    });
                    const data = await response.json();
                    if (response.ok) {
                        currentUser = username;
                        localStorage.setItem('currentUser', username);
                        messageEl.innerHTML = '<div class="alert alert-success">✅ Login successful!</div>';
                        setTimeout(() => updateUIForLoggedInUser(), 500);
                    } else {
                        messageEl.innerHTML = `<div class="alert alert-error">❌ ${data.error}</div>`;
                    }
                } catch (error) {
                    messageEl.innerHTML = '<div class="alert alert-error">❌ Error logging in.</div>';
                }
            }
        }

        // Logout user
        function logout() {
            if (!confirm('⚠️ Are you sure you want to logout?')) {
                return;
            }
            
            currentUser = null;
            localStorage.removeItem('currentUser');
            document.getElementById('loginSection').style.display = 'block';
            document.getElementById('registerSection').style.display = 'none';
            document.getElementById('userProfile').style.display = 'none';
            document.getElementById('currentUser').style.display = 'none';
            document.getElementById('addReviewForm').style.display = 'none';
            document.getElementById('loginUsername').value = '';
            document.getElementById('loginPassword').value = '';
            document.getElementById('authMessage').innerHTML = '';
            alert('✅ Logged out successfully!');
        }

        // Update UI for logged in user
        function updateUIForLoggedInUser() {
            document.getElementById('loginSection').style.display = 'none';
            document.getElementById('registerSection').style.display = 'none';
            document.getElementById('userProfile').style.display = 'block';
            document.getElementById('profileUsername').textContent = currentUser;
            document.getElementById('usernameDisplay').textContent = currentUser;
            document.getElementById('currentUser').style.display = 'flex';
        }

        // Toggle between login and register
        function toggleAuth() {
            const loginSection = document.getElementById('loginSection');
            const registerSection = document.getElementById('registerSection');
            
            if (loginSection.style.display === 'none') {
                loginSection.style.display = 'block';
                registerSection.style.display = 'none';
                document.getElementById('authMessage').innerHTML = '';
            } else {
                loginSection.style.display = 'none';
                registerSection.style.display = 'block';
                document.getElementById('registerMessage').innerHTML = '';
            }
        }

        // Enter key support for search
        document.getElementById('searchQuery').addEventListener('keypress', function(e) {
            if (e.key === 'Enter') {
                searchBooks();
            }
        });

        // Enter key support for review ISBN
        document.getElementById('reviewISBN').addEventListener('keypress', function(e) {
            if (e.key === 'Enter') {
                loadReviews();
            }
        });

        // Enter key support for login
        document.getElementById('loginPassword').addEventListener('keypress', function(e) {
            if (e.key === 'Enter') {
                login();
            }
        });

        // Enter key support for register
        document.getElementById('regPassword').addEventListener('keypress', function(e) {
            if (e.key === 'Enter') {
                register();
            }
        });
    </script>
</body>
</html>
