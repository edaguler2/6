# 6
6
<! DOCTYPE  çerçeve kümesi SİSTEMİ "frameset.dtd">
< çerçeve kümesi >
  < yüklem  lemma = " kaçırma " >
    < roleset  id = " abduct.01 "  name = " birini zorla götürmek için " >
      < takma adlar >
        < alias  framenet = "  Adam kaçırma " pos = " v "  verbnet = " 10.5 " >kaçırma</ alias >
        < alias  framenet = "  Adam kaçırma " pos = " n "  verbnet = " " >kaçırma</ alias >
        < alias  framenet = " Kaçırma "  pos = " j "  verbnet = " " >kaçırıldı</ alias >
      </ takma adlar >
      < not >ABDUCT-V NOTLAR: Vncls üyesi çalma-10.5. FN sınıfı Kaçırma. (abduct.01-v'den)</ not >
      < not >ABDUCTION-N NOTLAR: Çerçeveli Claire. FrameNet Kaçırma. abduct.01 fiil girişine dayalıdır. (abduction.01-n'den)</ not >
      < roller >
        < Rol  descr = " madde "  f = " pag "  n = " 0 " >
          < vnrole  vncls = " 10.5 "  vntheta = " aracı " />
        </ rol >
        < role  descr = " kaçırılan kişi "  f = " ppt "  n = " 1 " >
          < vnrole  vncls = " 10.5 "  vntheta = " tema " />
        </ rol >
      </ roller >
      < örnek  isim = " abduct-v: geçişli (çocuğu kaçırmak için yazılı izin mi almalıydı?) "  src = " "  type = " - " >
        < text > Avukatı, havaalanında ona bir mektup yazdı ve bir kopyasıyla gümrük yetkililerine, Bella'nın içki içtiğine ve her halükarda kaçırdığı [çocuğun] bakımını yapmaya uygun olmadığına dair kanıtları olduğunu söyledi. *-1 yazılı izin olmadan.</ metin >
        < arg  f = " "  n = " 0 " >o</ arg >
        < arg  f = " dis "  n = " m " >her neyse</ arg >
        < rel  f = " " >kaçırıldı</ rel >
        < arg  f = " "  n = " 1 " >*trace*-1 (= kim)</ arg >
        < arg  f = " mnr "  n = " m " >yazılı izin olmadan</ arg >
      </ örnek >
      < örnek  ad = " abduction-n: Tüm argümanlar "  src = " web "  type = " " >
        < bükülme  yönü = " ns "  form = " ns "  kişi = " ns "  zaman = " ns "  ses = " ns " />
        < text >Bu olayın birkaç hesabı var; ancak, hepsi bir Amazon kraliçesini kaçırması etrafında toplanıyor.</ text >
        < arg  f = " "  n = " 0 " >onun</ arg >
        < rel  f = " " >kaçırma</ rel >
        < arg  f = " "  n = " 1 " >bir Amazon kraliçesi.</ arg >
      </ örnek >
    </ rol seti >
    < roleset  id = " abduct.02 "  name = " merkezi bir eksenden uzaklaş " >
      < takma adlar >
        < alias  framenet = " "  pos = " v "  verbnet = " " >kaçırma</ alias >
        < alias  framenet = " "  pos = " n "  verbnet = " " >kaçırma</ alias >
      </ takma adlar >
      < not >ABDUCTION-N NOTLAR: Kekik ve Sharp verilerine dayanmaktadır. Karşılaştırma yok. Katie tarafından çerçevelendi. (abduction.02-n'den) VNcl yok, FN. </ not >
      < roller >
        < Rol  descr = " taşıyıcı "  f = " pag "  n = " 0 " />
        < role  descr = " şey taşındı "  f = " ppt "  n = " 1 " />
      </ roller >
      < örnek  ad = " abduction-n: Her iki argüman da "  src = " "  type = " " >
        < bükülme  yönü = " ns "  form = " ns "  kişi = " ns "  zaman = " ns "  ses = " ns " />
        < text >Sol kolunu kaçırması bozulmuş.</ text >
        < arg  f = " "  n = " 0 " >Onun</ arg >
        < rel  f = " " >kaçırma</ rel >
        < arg  f = " "  n = " 1 " >sol kolun</ arg >
      </ örnek >
    </ rol seti >
  </ yüklem >
</ çerçeve kümesi >
