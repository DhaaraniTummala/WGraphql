# WPGraphQL

WPGraphQL is a free, open-source WordPress plugin that turns your WordPress site into a GraphQL API.

![WPGraphQL Banner](.github/wp-graphql-banner.png)

## ⚡️ What is GraphQL?

[GraphQL](https://graphql.org/) is a query language for APIs and a runtime for fulfilling those queries with your existing data. It gives clients the power to ask for exactly what they need — nothing more, nothing less — and makes APIs fast, flexible, and developer-friendly.

## 📦 What is WPGraphQL?

WPGraphQL is a WordPress plugin that adds a GraphQL API to your WordPress site.

This allows developers to:
- Fetch content from WordPress using GraphQL queries
- Replace or supplement the REST API
- Integrate WordPress with modern JavaScript frameworks like React, Vue, or Gatsby

## ✅ Features

- Full CRUD access to posts, pages, categories, tags, users, menus, media, etc.
- Extensible through custom post types, taxonomies, fields, and resolvers
- Works with popular plugins like ACF, WooCommerce, and Yoast via extensions
- Strongly typed schema with introspection support
- Developer-friendly tools and GraphiQL explorer

## 🚀 Getting Started

### 1. Installation

From the WordPress Admin:

1. Go to **Plugins > Add New**
2. Search for **WPGraphQL**
3. Click **Install Now**
4. Activate the plugin

Or install via Composer:

```bash
composer require wp-graphql/wp-graphql
```

### 2. Query Your Site

Once activated, visit:

```
https://yoursite.com/graphql
```

Try out GraphiQL Explorer:

```
https://yoursite.com/wp-admin/tools.php?page=wp-graphql-graphiql
```

## 📚 Documentation

- [Official Docs](https://www.wpgraphql.com/docs/)
- [GraphQL Language](https://graphql.org/learn/)
- [Schema Explorer](https://api.wpgraphql.com)

## 🛠 Extending WPGraphQL

You can add custom types, fields, resolvers, and mutations using PHP. See the [Extending WPGraphQL Guide](https://www.wpgraphql.com/docs/extending/) for details.

There are also community plugins that extend WPGraphQL:

- [WPGraphQL for Advanced Custom Fields](https://github.com/wp-graphql/wp-graphql-acf)
- [WPGraphQL for WooCommerce](https://github.com/wp-graphql/wp-graphql-woocommerce)

## 🤝 Contributing

Contributions are welcome!

- Read the [Contributing Guide](CONTRIBUTING.md)
- Browse open [issues](https://github.com/wp-graphql/wp-graphql/issues)
- Submit pull requests to help improve the project

You can also support the project financially via sponsorship:
[💖 Sponsor WPGraphQL](https://github.com/sponsors/jasonbahl)

## 🧪 Running Tests

We use PHPUnit for backend testing:

```bash
composer install
composer run test
```

For JavaScript testing:

```bash
npm install
npm run test
```

## 📄 License

WPGraphQL is released under the [MIT License](LICENSE.md).

---

Made with ❤️ by [Jason Bahl](https://github.com/jasonbahl) and contributors.
