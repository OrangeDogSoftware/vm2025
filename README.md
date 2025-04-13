# VM2025

Une implémentation de machine virtuelle écrite en Rust.

## Démarrage

### Prérequis

Assurez-vous d'avoir Rust installé sur votre système. Si ce n'est pas le cas, vous pouvez l'installer en utilisant [rustup](https://rustup.rs/).

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

### Construction du projet

```bash
# Cloner le dépôt
git clone https://github.com/OrangeDogSoftware/vm2025.git
cd vm2025

# Construire le projet
cargo build

# Exécuter le projet
cargo run
```

## Structure du projet

- `src/main.rs`: Point d'entrée de l'application
- `Cargo.toml`: Configuration du projet et dépendances

## Fonctionnalités prévues

- Implémentation d'un bytecode simple
- Interpréteur de machine virtuelle
- Jeu d'instructions personnalisable
- Support pour différents types de données
