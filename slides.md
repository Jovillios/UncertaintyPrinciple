---
marp: true
theme: uncover
math: mathjax
paginate: true
---

# Principe d'incertitude d'Heisenberg

Jules Decaestecker & Tiban Dorel

---

## Sommaire

1. Introduction
2. Principe d'incertitude pour la transformée de Fourier
3. Principe d'incertitude pour la transformée de Laplace
4. Principe d'incertitude pour la transformée en ondelettes
5. Conclusion


---

## Introduction

- Le principe d'incertitude est un principe fondamental de la mécanique quantique.

- Il a été formulé par Werner Heisenberg en 1927.

- Il stipule que l'on ne peut pas connaître simultanément la position et la quantité de mouvement d'une particule.

---

## Principe d'incertitude pour la transformée de Fourier

- La transformée de Fourier est une transformation mathématique qui permet de passer d'une fonction du temps à une fonction de la fréquence.

- Elle est définie par la formule suivante :

$$
\hat{f}(\xi) = \int_{-\infty}^{\infty} f(x) e^{-2i\pi x \xi} dx

$$

---

## Principe d'incertitude pour la transformée de Fourier

- Le principe d'incertitude pour la transformée de Fourier stipule que l'on ne peut pas connaître simultanément la position et la quantité de mouvement d'une particule.

- Plus précisément, il stipule que si une fonction est très localisée dans le domaine temporel, alors sa transformée de Fourier sera très étalée dans le domaine fréquentiel, et vice versa.

---

## Principe d'incertitude pour la transformée de Laplace

- La transformée de Laplace est une transformation mathématique qui permet de passer d'une fonction du temps à une fonction de la fréquence complexe.

- Elle est définie par la formule suivante :

$$
\hat{f}(s) = \int_{0}^{\infty} f(t) e^{-st} dt

$$

---

## Principe d'incertitude pour la transformée de Laplace

- Le principe d'incertitude pour la transformée de Laplace stipule que l'on ne peut pas connaître simultanément la position et la quantité de mouvement d'une particule.

- Plus précisément, il stipule que si une fonction est très localisée dans le domaine temporel, alors sa transformée de Laplace sera très étalée dans le domaine fréquentiel complexe, et vice versa.

---

## Principe d'incertitude pour la transformée en ondelettes

- La transformée en ondelettes est une transformation mathématique qui permet de passer d'une fonction du temps à une fonction de l'échelle et du décalage.

- Elle est définie par la formule suivante :

$$
\hat{f}(a,b) = \int_{-\infty}^{\infty} f(t) \psi_{a,b}(t) dt

$$

---

## Principe d'incertitude pour la transformée en ondelettes

- Le principe d'incertitude pour la transformée en ondelettes stipule que l'on ne peut pas connaître simultanément la position et la quantité de mouvement d'une particule.

- Plus précisément, il stipule que si une fonction est très localisée dans le domaine temporel, alors sa transformée en ondelettes sera très étalée dans le domaine de l'échelle et du décalage, et vice versa.

---

## Conclusion

- Le principe d'incertitude est un principe fondamental de la mécanique quantique.

- Il stipule que l'on ne peut pas connaître simultanément la position et la quantité de mouvement d'une particule.

- Il a été formulé par Werner Heisenberg en 1927.


---

```python

def main():
    print("Merci pour votre attention !")

if __name__ == "__main__":
    main()

```
