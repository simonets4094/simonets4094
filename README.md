- 👋 Hi, I’m @simonets4094
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
simonets4094/simonets4094 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

        http://wiki.mbalib.com/wi     {
    "_id": null,
    "home_page": "https://github.com/tunga3109/python-capitalcom",
    "name": "capitalcom-python",
    "maintainer": "",
    "docs_url": null,
    "requires_python": ">=3.5",
    "maintainer_email": "",
    "keywords": "capitalcom exchange rest api bitcoin ethereum btc eth",
    "author": "Tung Chan",
    "author_email": "",
    "download_url": "",
    "platform": null,
    "description": "Welcome to unofficial Python wrapper for the Capital.com exchange REST API v1. Use at your own risk.\n\nThe Capital.com API allows direct access to the latest version of our trading engine.\n\n--- General information\n\nBase URL: https://api-capital.backend-capital.com/ Base demo URL: https://demo-api-capital.backend-capital.com/ In order to use the endpoints a session should be launched. This can be done using the POST /session endpoint. Session is active for 10 minutes. In case your inactivity is longer than this period then an error will occur upon next request. The API covers the full range of available instruments, licences and trading functionality. Getting started\n\n--- To use the API the following simple steps should be taken:\n\nCreate a trading account Note that a demo account can be used. Turn on Two-Factor Authentication (2FA) 2FA should be turned on prior to API key generation. Instruction for 2FA enabling. Generate an API key To generate the API key, go to Settings > API integrations > Generate new key. There you will need to enter the label of the key, set an optional expiration date, enter the 2FA code and that\u2019s it. You are all set! Authentication\n\n--- How to start new session?\n\nThere are 2 ways to start the session:\n\nUsing your API key, login and password details.\nUsing your API key, login and encrypted password details.\n-- Using your API key, login and password details\n\nHere you should simply use the POST /session endpoint and mention the received in the platform\u2019s Settings API key in the X-CAP-API-KEY header, login and password info in the identifier and password parameters. The value of the encryptionKey parameter should be false.\n\n-- Using your API key, login and encrypted password details\n\nFirst of all you should use the GET /session/encryptionKey and mention the generated in the platform\u2019s Settings API key in the X-CAP-API-KEY header. As a response you will receive the encryptionKey and timeStamp parameters; Using the received encryptionKey and timeStamp parameters you should encrypt your password using the AES encryption method.\n\nGo to the POST /session endpoint, set true value for the encryptionKey parameter and mention the received in the platform\u2019s Settings API key in the X-CAP-API-KEY header, login and prior encrypted password info in the identifier and password parameters\n\n--- After starting the session\n\nOn starting the session you will receive the CST and X-SECURITY-TOKEN parameters in the response headers. CST is an authorization token, X-SECURITY-TOKEN shows which financial account is used for the trades. These headers should be passed on subsequent requests to the API. Both tokens are valid for 10 minutes after the last use.\n",
    "bugtrack_url": null,
    "license": "MIT",
    "summary": "Capital.com REST API python implementation",
    "version": "0.2.3",
    "project_urls": {
        "Homepage": "https://github.com/tunga3109/python-capitalcom"
    },
    "split_keywords": [
        "capitalcom",
        "exchange",
        "rest",
        "api",
        "bitcoin",
        "ethereum",
        "btc",
        "eth"
    ],
    "urls": [
        {
            "comment_text": "",
            "digests": {
                "blake2b_256": "3715e9494f4c1d0644031ecf5b64f2a66379b8d9f7307de210270c55d3c045dc",
                "md5": "1500718b7e97370dd94c127fe82b4850",
                "sha256": "c89be918dc552b3a42097aca05a431007e11dafb6f2f921b4e8d899dfc5c39de"
            },
            "downloads": -1,
            "filename": "capitalcom_python-0.2.3-py3-none-any.whl",
            "has_sig": false,
            "md5_digest": "1500718b7e97370dd94c127fe82b4850",
            "packagetype": "bdist_wheel",
            "python_version": "py3",
            "requires_python": ">=3.5",
            "size": 11771,
            "upload_time": "2023-12-25T21:33:28",
            "upload_time_iso_8601": "2023-12-25T21:33:28.318734Z",
            "url": "https://files.pythonhosted.org/packages/37/15/e9494f4c1d0644031ecf5b64f2a66379b8d9f7307de210270c55d3c045dc/capitalcom_python-0.2.3-py3-none-any.whl",
            "yanked": false,
            "yanked_reason": null
        }
    ],
    "upload_time": "2023-12-25 21:33:28",
    "github": true,
    "gitlab": false,
    "bitbucket": false,
    "codeberg": false,
    "github_user": "tunga3109",
    "github_project": "python-capitalcom",
    "travis_ci": false,
    "coveralls": false,
    "github_actions": false,
    "requirements": [],
    "lcname": "capitalcom-python"
}
        
Tung Chan Tung Chan
El
        
