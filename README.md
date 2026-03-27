# HashCrcker-Pro
## HashCracker-Pro - Advanced Password Hash Cracking Framework

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Code Style](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Security](https://img.shields.io/badge/security-ethical-red)](https://github.com/E11SX/hashcracker-pro)
[![Downloads](https://img.shields.io/badge/downloads-latest-brightgreen)](https://github.com/yE11SX/hashcracker-pro/releases)

A professional-grade password hash cracking framework with multiple attack modes, rule-based transformations, session management, and enterprise-ready features. Designed for security professionals and penetration testers.

#  Features

### __Intelligent Hash Detection__
- Auto-detects 15+ hash types (MD5, SHA1-512, bcrypt, NTLM, MySQL, etc.)
- Base64 encoded hash support
- Regex-based pattern matching
- Multiple algorithm suggestions

#### __Multiple Attack Modes__
- **Dictionary Attack** - Wordlist-based with rule engine
- **Brute Force** - Character set permutations
- **Hybrid Attack** - Dictionary + mutations
- **Mask Attack** - Pattern-based (e.g., ?l?l?d?d)
- **Rainbow Tables** - Pre-computed hash lookup
- **Multi-Process** - Parallel processing (CPU cores)

### __Advanced Rule Engine__
- 15+ built-in transformation rules
- Custom rule support
- Leetspeak conversion
- Case permutations
- Year/number appending
- Common prefix/suffix
- Toggle case variations

### __Session Management__
- Save/restore cracking sessions
- Resume from any position
- Progress tracking
- JSON session storage
- Auto-save on interrupt

### __Comprehensive Reporting__
- Detailed execution reports
- Performance metrics (hashes/sec)
- Success/failure analysis
- JSON/CSV/HTML export
- Session logs

 ### __Performance Optimizations__
- Multi-processing support
- Memory-efficient streaming
- Progress bars with tqdm
- Rate limiting controls
- Timeout management

## Quick Start

## Installation

```bash
# clone repository
git clone https://github.com/E11SX/hashcracker-pro.git
cd hashcracker-pro

# Install dependencies
pip install -r requirements.txt

# Install optional dependencies for advanced features
pip install bcrypt passlib cryptography
