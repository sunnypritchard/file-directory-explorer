<style>
    .readme-flex {
        display: flex;
        align-items: center;
        justify-content: space-between;
        background-color: rgb(91, 94, 106);
        padding: 24px;
        gap: 24px;
    }
    .readme-flex > div {
        flex: 1;
    }
    .readme-flex img {
        max-width: 100%;
        height: auto;
    }
    @media (max-width: 700px) {
        .readme-flex {
            flex-direction: column;
            text-align: center;
        }
        .readme-flex > div {
            text-align: center;
        }
    }
</style>
![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Flask](https://img.shields.io/badge/flask-1.1%2B-green)
![License](https://img.shields.io/badge/license-MIT-green)

<div class="readme-flex">
    <div>
        <h1>File/Directory Explorer</h1>
        <p>
            This is web application built with flask that interacts with the file system to allow users to explore and manage files and directories.
        </p>
    </div>
    <div>
        <img src="app/static/readme.png" alt="Flask File Directory Explorer Screenshot" width="384" height="216" />
    </div>
</div>
