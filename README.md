# Rabbit-Rust(Un Official)
![Logo](https://avatars3.githubusercontent.com/u/11961573?v=3&s=100)

[![Build Status](https://travis-ci.org/winhtaikaung/rabbit-rust.svg?branch=master)](https://travis-ci.org/winhtaikaung/rabbit-rust)

**Zawgyi <=> Unicode Converter for Rust Lang(Rust)**
## Usage


```rust

#[path = "./rabbit/rabbit.rs"]
pub mod rabbit;

fn main() {
    rabbit::zg2_uni("သီဟိုဠ္မွ ဉာဏ္ႀကီးရွင္သည္ အာယုဝၯနေဆးၫႊန္းစာကို ဇလြန္ေဈးေဘး ဗာဒံပင္ထက္ အဓိ႒ာန္လ်က္ ဂဃနဏဖတ္ခဲ့သည္။");
    rabbit::uni2_zg("သီဟိုဠ်မှ ဉာဏ်ကြီးရှင်သည် အာယုဝဍ္ဎနဆေးညွှန်းစာကို ဇလွန်ဈေးဘေး ဗာဒံပင်ထက် အဓိဋ္ဌာန်လျက် ဂဃနဏဖတ်ခဲ့သည်။");
}


```

## Contributing

1. Fork it ( https://github.com/winhtaikaung/rabbit-rust )

2) Create your feature branch (`git checkout -b my-new-feature`)

3. Commit your changes (`git commit -am 'Add some feature'`)

4) Push to the branch (`git push origin my-new-feature`)

5. Create a new Pull Request

## License

MIT
