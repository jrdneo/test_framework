# Automation Framework Development Checklist

## 1. Smoke Tests
- [x] Load homepage and verify title/logo is visible
- [ ] Verify main menu items are visible (Books, Cart, Login)
- [ ] Verify search bar is visible and functional
- [ ] Search for a book and verify search results appear
- [ ] Click on a book from search results and verify navigation to book details page
- [ ] Add a book to cart and verify cart count updates
- [ ] View cart and verify correct item and price appear

## 2. UI Element Validation
- [ ] Verify categories list is visible on homepage
- [ ] Verify each book card shows title, price, and Add to Cart button
- [ ] Verify cart page shows subtotal and checkout button

## 3. Functional Scenarios
- [ ] Search and purchase a book flow (search, add to cart, checkout)
- [ ] Add multiple books and remove one from cart
- [ ] Search for a non-existent book and verify "no results" message

## 4. (Optional) Authentication Tests
- [ ] Login with valid user credentials
- [ ] Attempt login with invalid credentials and verify error message

---

### Bonus:
- [ ] Setup Playwright config with baseURL and test timeout
- [ ] Implement Page Object Model for HomePage, BookDetailsPage, CartPage
- [ ] Setup CI workflow to run tests automatically on push (GitHub Actions)
- [ ] Add detailed README explaining framework and how to run tests
