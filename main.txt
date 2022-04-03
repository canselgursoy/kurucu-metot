using System;
namespace sinif_kavrami
{
    class Program
    {
        static void Main(string [] args)
        {
            //Söz Dizimi
            //class SinifAdi

           // {
               //[Erişim Belirleyici] [Veri Tipi] OzellikAdi;
               //[Erişim Belirleyici] [Geri Dönüş Tipi] MetotAdi([ParametreListesi])
               
               //{
                      //Metot Komutları
              // }

            //}

            //Erişim Belirleyiciler
            //*Public---her yerden erişilebilir
            //*Private---sadece tanımlandığı sınıf içerisinde erişilebilir metotlar
            //*Internal---sadece bulunduğu proje içerisinde
            //*Protected---sadece tanımlandığı sınıfta veya o sınıftan kalıtım alan diğer sınıflar


            Calisan calisan1 = new Calisan();
            calisan1.Ad = "Cansel";
            calisan1.Soyad = "Gürsoy";
            calisan1.No = 0202160027;
            calisan1.Departman = "Mimar";
            calisan1.CalisanBilgileri();
        
            Console.WriteLine("******************");

            Calisan calisan2 = new Calisan();
            calisan2.Ad = "Leyla";
            calisan2.Soyad ="Gürsoy";
            calisan2.No = 02056304547;
            calisan2.Departman = "İk";
            calisan2.CalisanBilgileri();
            






        }
    }

    class Calisan
    {
        public string Ad;
        public string Soyad;
        public int No;
        public string Departman;


        public void CalisanBilgileri()
        {
            Console.WriteLine("Çalışanın Adı:{0} " ,Ad);
            Console.WriteLine("Çalışanın Soyadı:{0} " ,Soyad);
            Console.WriteLine("Çalışanın Numarası:{0} " ,No);
            Console.WriteLine("Çalışanın Departmanı:{0} " ,Departman);


        }        

    }
}
