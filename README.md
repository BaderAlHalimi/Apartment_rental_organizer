************************************
<h1 style="color:blue">Developed By: <a href="https://mostaql.com/u/BaderHalimi">Bader Al-Halimi</a></h1>

************************************

# Tenant and Building Management System

This project is a comprehensive web application for managing tenants, buildings, apartments, and payment invoices. It is developed for a client on the Mostaql platform.

## Features

- **Tenant Management**: Add, update, and remove tenant details.
- **Building Management**: Manage buildings, including adding new buildings and updating existing ones.
- **Apartment Management**: Track apartments, assign them to buildings, and manage apartment-specific details.
- **Invoice Management**: Create, update, and track payment invoices for tenants.

## Installation

1. **Clone the repository**
    ```sh
    git clone https://github.com/yourusername/tenant-management-system.git
    cd tenant-management-system
    ```

2. **Install dependencies**
    ```sh
    composer install
    npm install
    npm run dev
    ```

3. **Set up environment variables**
    Copy `.env.example` to `.env` and update the configuration values as needed.
    ```sh
    cp .env.example .env
    php artisan key:generate
    ```

4. **Run migrations**
    ```sh
    php artisan migrate
    ```

5. **Serve the application**
    ```sh
    php artisan serve
    ```

## Usage

After setting up the project, you can access the application at `http://localhost:8000`. The main functionalities include:

- **Dashboard**: Overview of tenants, buildings, apartments, and invoices.
- **Tenants**: Manage tenant information and view payment history.
- **Buildings**: Add and manage buildings, including associated apartments.
- **Apartments**: Assign apartments to buildings and manage apartment details.
- **Invoices**: Generate and track payment invoices for tenants.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any inquiries or feedback, please contact me at your-email@example.com.

---

*Developed by [Bader Al-Halimi](https://mostaql.com/u/BaderHalimi)*
