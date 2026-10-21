# Shell, Init Files, Variables and Expansions

Projet de scripts Bash du projet 4 "Shell, init files, variables and expansions" portant sur la gestion du shell, l'initialisation des fichiers, les variables d'environnement, les variables locales, l'arithmétique et les conversions de base.

## Description des Scripts


| `0-alias` | Définit un alias (`ls` pour `rm -f *`). | `alias ls='rm -f *'` |

| `1-hello_you` | Affiche `hello user` avec l'utilisateur Linux actuel. | `echo "hello $USER"` |

| `2-path` | Ajoute `/action` à la variable `PATH`. | `export PATH="$PATH:/action"` |

| `3-paths` | Compte le nombre de répertoires présents dans `PATH`. | `echo $PATH \| tr ':' '\n' \| grep / \| wc -l` |

| `4-global_variables` | Liste toutes les variables d'environnement. | `printenv` |

| `5-local_variables` | Liste les variables locales, d'environnement et les fonctions. | `set` |

| `6-create_local_variable` | Crée une variable locale `BEST="School"`. | `BEST="School"` |

| `7-create_global_variable` | Crée une variable globale/environnement `BEST="School"`. | `export BEST="School"` |

| `8-true_knowledge` | Affiche le résultat de $128 + \text{TRUEKNOWLEDGE}$. | `echo $((TRUEKNOWLEDGE + 128))` |

| `9-divide_and_rule` | Affiche le résultat de $\text{POWER} / \text{DIVIDE}$. | `echo $((POWER / DIVIDE))` |

| `10-love_exponent_breath` | Affiche le résultat de $\text{BREATH}^{\text{LOVE}}$. | `echo $((BREATH ** LOVE))` |

| `11-binary_to_decimal` | Convertit un nombre binaire (base 2) stocké dans `BINARY` en décimal (base 10). | `echo $((2#$BINARY))` |

| `12-combinations` | Affiche toutes les combinaisons de deux lettres de `aa` à `zz`, à l'exception de `oo`. | `printf "%s\n" {a..z}{a..z} \| grep -v oo` |

| `13-print_float` | Affiche un nombre (`NUM`) avec deux décimales. | `printf "%.2f\n" "$NUM"` |

| `14-decimal_to_hexadecimal` | Convertit un nombre décimal (`DECIMAL`) en hexadécimal (base 16). | `printf "%x\n" "$DECIMAL"` |

