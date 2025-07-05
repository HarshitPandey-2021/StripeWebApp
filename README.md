💳 Stripe WebApp – Payment Gateway in C#

A lightweight web application demonstrating how to integrate Stripe payment gateway using C# and ASP.NET. It securely handles payment form submission, tokenization, and payment confirmation using Stripe's API.

🔍 Features

- Stripe Checkout integration using test keys
- Payment form with dynamic amount input
- Tokenization and secure client-server communication
- Payment success/failure handling with redirection
- ASP.NET MVC structured backend
- Clean frontend form (Razor view)

 🧰 Tech Stack

| Layer     | Tech                |
|-----------|---------------------|
| Backend   | C#, ASP.NET MVC     |
| Frontend  | Razor Views, HTML/CSS |
| Payment API | Stripe (Test Mode) |
| Tools     | Visual Studio, GitHub |


 📂 Key Files

- `StripeWebApp/Controllers/PaymentController.cs`: Handles payment routing
- `Views/Home/Index.cshtml`: Frontend payment form
- `appsettings.json`: Environment keys config (hidden in `.gitignore`)
