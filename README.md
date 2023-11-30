# React Hooks: useMemo ve useCallback Örneği

Bu repo, React Hooks olan `useMemo` ve `useCallback`'un kullanımını gösteren bir örneği içerir.

## İçerik

Bu projede, ağır hesaplamalar yapan bir fonksiyonun (`wrapperFunction`) nasıl optimize edileceğini gösteriyoruz. Bu fonksiyon, `useMemo` ve `useCallback` Hooks ile kullanılır.

`App` componenti içinde, `useMemo` ve `useCallback` Hooks'un kullanımını görebilirsiniz. `useMemo`, `wrapperFunction`'ın sonucunu hafızada tutar ve sadece gerekli olduğunda yeniden hesaplar. `useCallback` ise `wrapperFunction`'ın referansını hafızada tutar ve sadece gerekli olduğunda yeniden oluşturur.

## Kullanım

Projeyi klonladıktan sonra, aşağıdaki komutları çalıştırın:

```bash
npm install
npm start
```
