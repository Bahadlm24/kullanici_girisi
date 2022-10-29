# kullanici_girisi

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        String username,password;

        Scanner inp = new Scanner(System.in);

        System.out.println("Kullanıcı Adınız : ");
        username = inp.nextLine();

        System.out.println("Şifreniz : ");
        password = inp.nextLine();

        if (username.equals("patika")&& password.equals("java123")){
            System.out.println("Giriş yaptınız !");
        }else {
            System.out.println("bilgileriniz yanlış");
        }
    }
}
