## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

Hãy sử dụng app router và pokeapi (https://pokeapi.co) để tạo danh sách format bằng cách sử dụng table
_ Hãy sử dụng shadcn/ui rồi thêm component Table
_ Table thì bao gồm các mục như sau: id, name, image (sprites.front_default), type name
_ Table cơ bản có 50 mục, nếu user scroll tới cuối và liên tục như vậy thì hãy thêm mỗi 50 mục
_ Data ban đầu được lấy bằng RSC
_ Sau đó data được lấy từ @tanstack/react-query의 infiniteQuery
_ Hãy dùng ky để tạo Class PokemonApi, sau đó tạo data layer và sử dụng \* Hãy dùng zod để kiểm chứng giá trị ky trong class PokemonApi
