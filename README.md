<div id="top"></div>

<!-- About the Project -->
<div align="center">
    <h2>United Atomic - Web Version</h2>
    <p>A complete RESTful API for Financial Institutions, developed with <a href="https://react.dev/">React</a> and <a href="https://nextjs.org/">Next.js</a>.</p>
    <a href="https://github.com/caard0s0/united-atomic-bank-client/issues">Report Bugs</a>
    &nbsp;&bull;&nbsp;
    <a href="https://github.com/caard0s0/united-atomic-bank-client/actions">Actions</a>
    &nbsp;&bull;&nbsp;
    <a href="https://github.com/caard0s0/united-atomic-bank-client/pulls">Pull Requests</a>
</div>

&nbsp;

![db_diagram](https://github.com/caard0s0/united-atomic-bank/assets/95318788/1032912b-ea59-4588-b1e8-5c79c2409d4a)

A Financial Software specialized in the intermediation of money between savers and those in need of loans, as well as in the custody of that money. It was created following SOLID principles, for better scalability and code maintenance. In addition, thinking about a reliable and well-tested application, with Unit and Automated Tests using Mock DB, the tests apply the concept of DB Stubs. Deploying it using Amazon's Cloud services.

&nbsp;

<h3>Built With</h3>

[![Tech Tools](https://skillicons.dev/icons?i=html,tailwind,ts,react,nextjs)](https://skillicons.dev)

<!-- Table of Contents -->
<details>
  <summary>Table of Contents</summary>
    <ol>
        <li>
            <a href="#getting-started">Getting Started</a>
            <ul>
                <li><a href="#installation">Installation</a></li>
                <li><a href="#usage">Usage</a></li>
            </ul>
        </li>
        <li><a href="#license">License</a></li>
        <li><a href="#contact">Contact</a></li>
    </ol>
</details>

&nbsp;

<!-- Getting Started -->
<h2 id="getting-started">Getting Started</h2>

<p>To get started, You need to have <strong>Node.js 18+</strong> installed on your machine, for more information visit <a href="https://nodejs.org/en/download">Node.js Downloads</a>.

<p><strong>OBS:</strong> This guide is designed to run this project locally (Local Development), on Linux-based systems.</p>

<!-- Installation -->
<h3 id="installation">Installation</h3>

1. Clone the repository.

    ```bash
    git clone https://github.com/caard0s0/united-atomic-bank-client.git
    ```

2. Install <strong>Golang-Migrate</strong> as CLI. for more information visit <a href="https://github.com/golang-migrate/migrate/tree/master/cmd/migrate">Golang CLI Documentation</a>.

3. Create an `.env.local` file with environment variables.

    <strong>WARNING:</strong> The values ​​below are for testing purposes only, please change them in the future.

    ```bash
    cat > app.env << EOF
    SERVER_PORT=8080
    HTTP_SERVER_ADDRESS=http://localhost:$SERVER_PORT
    EOF
    ```

4. Install <strong>GoMock</strong> and be able to use the <strong>MockGen</strong> tool.

    - Framework installation.

        ```bash
        go install github.com/golang/mock/mockgen@v1.6.0
        ```

    - add a PATH to your <strong>go/bin</strong> folder in the `~/.zshrc` file or another Shell.

        <strong>WARNING:</strong> This PATH below is just an example.

        ```bash
        export PATH=$PATH:~/.asdf/installs/golang/1.21.0/packages/bin
        ```

5. Install <strong>SQLC</strong>. for more information visit <a href="https://docs.sqlc.dev/en/latest/index.html">SQLC Documentation</a>.

<!-- Usage -->
<h2 id="usage">Usage</h2>

<p>After completing the installation, you can run the project.</p>

1. Create and run the <strong>Containers</strong>.

    ```cmd
    docker compose up -d
    ```

<br>

<!-- License -->
<h2 id="license">License</h2>

This project is being distributed under the <strong>MIT License</strong>, see `LICENSE.txt` for more information.

<br>

<!-- Contact -->
<h2 id="contact">Contact</h2>

-   Software Engineer
-   Vinicius Cardoso - <a href="mailto:cardoso.business.ctt@gmail.com">Email</a>

<p align="right">
    <a href="#top"> &uarr; back to top</a>
</p>
