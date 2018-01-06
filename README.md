# Php-cs-fixer Gitamine Plugin

## Requirements

* php >= 7.1
* php-cs-fixer
* Linux/Mac

## Installation

```bash
gitamine install git4min3/gitamine-php-cs-fixer    
```

## Configuration

* Only works on pre-commit events, also add it before executing the tests.

```yaml
# gitamine.yaml
gitamine:
  pre-commit:
    php-cs-fixer: ~    
```

```yaml
# gitamine.yaml
gitamine:
  pre-commit:
    php-cs-fixer:
      bin: bin/php-cs-fixer               #default php-cs-fixer    
```

