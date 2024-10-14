## Case:

Frontend Developer pozisyonu için hazırladığımız bu case'de sizden Next.js kullanarak bir çalışma hazırlamanızı istiyoruz.

## Tasarım:

```
https://www.figma.com/design/wFCPs7duH7jmNdcKtaiFGe/Frontend-Assignment?node-id=0-1&t=wvPIltN7QW136vwy-1
```

## API Endpoints:

### Posts API:

```
GET: https://iztek-frontend-assignment.vercel.app/api/posts.json
```

### References API:

```
GET: https://iztek-frontend-assignment.vercel.app/api/references.json
```

### Team API:

```
GET: https://iztek-frontend-assignment.vercel.app/api/team.json
```

### Cities API:

```
GET: https://iztek-frontend-assignment.vercel.app/api/cities.json
```

## Gereksinimler:

- Next.js kullanarak bir proje oluşturulması
- SSR (Server Side Rendering) kullanılması
- Homepage ve Filter sayfalarının tasarımın figma'dan alınarak oluşturulması
- Homepage'de yer alan Team alanının `Team API`'dan çekilerek listelenmesi
- Homepage'de yer alan References alanının `References API`'dan çekilerek listelenmesi
- Homepage'de yer alan References alanının slider şeklinde çalışması
- Homepage'de yer alan Search of location formu submit edildiğinde Filter sayfasına yönlendirilmesi ve query parametrelerinin gönderilmesi
- Filter sayfasında yer alan Show next butonunun fake infinite scroll veya fake pagination şeklinde çalışması (client-side pagination olması yeterli)
- Filter sayfasında yer alan Location, Search ve Price filtrelerinin çalışması (client-side filtre olması yeterli)
- Filter sayfasında yer alan Posts alanının `Posts API`'dan çekilerek listelenmesi
- Location select alanının `Cities API`'dan çekilerek doldurulması

## Olsa iyi olur olmasa da olur:

- Deploy edilmiş çalışan hali ve linki (Vercel, Netlify, Github Pages vb.)
- Mobil uyumlu olması
- Linting ve Prettier
- TypeScript

> [!NOTE]
> Araç ve teknoloji seçimlerinizde özgürsünüz, sadece Next.js kullanmanız gerekmektedir.
> Pure CSS, SCSS, TailwindCSS, Styled Components gibi teknolojileri kullanabilirsiniz.
> Merriweather font'unu Google Fonts üzerinden projenize dahil edebilirsiniz.
