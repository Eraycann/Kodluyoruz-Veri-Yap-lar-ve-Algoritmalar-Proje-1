# Insertion/Selection Sort

### Insertion Sort

> Q: [22, 27, 16, 2, 18, 6] -> Insertion Sort olarak verilen dizinin sort türüne göre aşamalarını yazınız.

> Q: Big-O gösterimini yazınız.
```
[22,27,16,2,18,6] -> Insertion Sort
---------------------------
[22,27,16,2,18,6]   
[22,27,16,2,18,6]   
[16,22,27,2,18,6]   
[2,16,22,27,18,6]   
[2,16,18,22,27,6]   
[2,6,16,18,22,27]   
---------------------------
Time Complexity:  O(n^2)
```

> **Q**: Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

Eğer Linear Search algoritmasını baz alırsak,

- **Average case:** Aradığımız sayının dizinin ortasında olması.
- **Worst case:** Aradığımız sayının dizinin sonunda olması.
- **Best case:** Aradığımız sayının dizinin en başında olması.

> **A**: Time Complexity: Dizi sıralandıktan sonra 18 sayısı ortada olduğu için cevap "Average Case"dir.  [2,6,16,18,22,27]  

> Örnek bir Insertion Sort:

<img width="400" height="480" src="https://miro.medium.com/v2/resize:fit:386/format:webp/1*4cdf0E2yyIbAhu3RVrpf8g.gif"></img>


### Selection Sort

> **Q**: [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
```
A:
[2, | 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3, | 5, 8, 7, 9, 4, 15, 6]
[2, 3, 4, | 8, 7, 9, 5, 15, 6]
[2, 3, 4, 5, | 7, 9, 8, 15, 6]
---
[2, 3, 4, 5, 6, | 9, 8, 15, 7]
[2, 3, 4, 5, 6, 7, | 8, 15, 9]
[2, 3, 4, 5, 6, 7, 8, | 15, 9]
[2, 3, 4, 5, 6, 7, 8, 9, | 15]
```

> Örnek bir Selection Sort:

<img width="400" height="480" src="https://miro.medium.com/v2/resize:fit:828/format:webp/1*5WXRN62ddiM_Gcf4GDdCZg.gif"></img>

## Patika Hesabım

[![Patika Profilim](https://img.shields.io/badge/Patika-Profilim-2ea44f?style=for-the-badge&logo=patika&logoColor=white)](https://academy.patika.dev/tr/profile)

### Hakkımda

- 💻 Yazılım Geliştirici
- 🌱 Şu anda yeni teknolojiler öğreniyorum
- 🤝 Açık kaynak projelere katkıda bulunmayı seviyorum

## İletişim

- [LinkedIn](https://www.linkedin.com/in/eraycan-sivri-827997226/)
- [E-posta](mailto:eraycansivri@hotmail.com)
