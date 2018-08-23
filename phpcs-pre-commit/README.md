# PHP pre-commit hook

Checks if your code is OK with PSR2, using PHP_CodeSniffer.

## Installation

Add to your `composer.json` the following:

```json
"repositories": [  
  { 
    "type" : "vcs", 
    "url" : "https://github.com/pagarme/git-hooks.git"  
  } 
],
"require-dev": {
  "pagarme/git-hooks": "dev-master"
},
"scripts": {
  "post-update-cmd": "bash vendor/pagarme/git-hooks/phpcs-pre-commit/install.sh"
}
```

