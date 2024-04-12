# Dog Sınıfı
Bu Java sınıfı, bir köpeği temsil eder. Köpeğin adı ve yaşı gibi özellikleri bulunur. Ayrıca köpeğin havlaması ve bilgilerini yazdırması gibi işlevleri içerir.

## Kullanım
Sınıfı kullanmak için aşağıdaki adımları izleyin:

1. `Dog` sınıfını projenize dahil edin.
2. Köpek nesneleri oluşturmak için `Dog` sınıfının yapıcılarını kullanın.
3. Köpeğin yaşını değiştirmek için `setAge(int age)` metodu kullanın. Köpeğin yaşını kontrol eder ve uygun aralıkta olup olmadığını kontrol eder.
4. Köpeğin adını ve yaşını yazdırmak için `info()` metodunu kullanın.
5. Köpeğin havlamasını sağlamak için `bark()` metodunu çağırın.

## Örnek

```java
public class Main {
    public static void main(String[] args) {
        // Köpek oluşturma
        Dog kopek1 = new Dog("Karabaş", 5);
        
        // Köpeğin bilgilerini yazdırma
        kopek1.info();
        
        // Köpeğin yaşını değiştirme
        kopek1.setAge(8);
        
        // Köpeğin tekrar bilgilerini yazdırma
        kopek1.info();
        
        // Köpeğin havlaması
        kopek1.bark();
    }
}
```

## Notlar
- Bu sınıf, köpekleri temsil etmek için kullanılır.
- Köpeğin adı ve yaşı gibi özelliklerine doğrudan erişim sağlanabilir.
- `setAge(int age)` metodu, köpeğin yaşını kontrol eder ve uygun aralıkta olup olmadığını kontrol eder.

--- 

Bu README dosyası, `Dog` sınıfının ne yaptığını, nasıl kullanılacağını ve hangi özelliklere sahip olduğunu açıklar. Ayrıca, kullanıcıya sınıfı kullanmak için gerekli adımları, örnek kullanımı ve dikkat edilmesi gereken notları içerir.
