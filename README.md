# My Github page

> [Link to page](https://itskhaled.github.io/)

## ME :)

https://itskhaled.github.io/#me

## RDF play results 

> <https://itskhaled.github.io/#me> <http://xmlns.com/foaf/0.1/givenName> "خالد"@ar, "Khaled"@en; <br />
>     &nbsp;&nbsp;&nbsp;&nbsp;<http://xmlns.com/foaf/0.1/familyName> "خالد"@ar, "Khaled"@en; <br />
>     &nbsp;&nbsp;&nbsp;&nbsp;<http://schema.org/birthDate> "2001-06-06"^^<http://schema.org/Date>; <br />
>     &nbsp;&nbsp;&nbsp;&nbsp;<http://schema.org/jobTitle> "Professional Procrastinator"; <br />
>     &nbsp;&nbsp;&nbsp;&nbsp;<http://schema.org/nationality> "Lebanese". <br />
> _:df_4_5 a <http://schema.org/Organization>; <br />
>    &nbsp;&nbsp;&nbsp;&nbsp; <http://schema.org/name> "Ghent University". <br />
> <https://itskhaled.github.io/#me> <http://schema.org/memberOf> _:df_4_5. <br />
> _:df_4_6 a <http://schema.org/Organization>; <br />
>     &nbsp;&nbsp;&nbsp;&nbsp;<http://schema.org/name> "Student". <br />
> <https://itskhaled.github.io/#me> <http://schema.org/memberOf> _:df_4_6. <br />
> _:df_4_7 a <http://schema.org/Organization>; <br />
>     &nbsp;&nbsp;&nbsp;&nbsp;<http://schema.org/name> "Course"; <br />
>     &nbsp;&nbsp;&nbsp;&nbsp;<http://schema.org/attendee> <https://pietercolpaert.be/teaching/kg/#2023-2024>. <br />
> <https://itskhaled.github.io/#me> <http://schema.org/memberOf> _:df_4_7; <br />
>     &nbsp;&nbsp;&nbsp;&nbsp;<http://schema.org/email> "khaled.khaled@ugent.be"; <br />
>     &nbsp;&nbsp;&nbsp;&nbsp;<http://xmlns.com/foaf/0.1/knows> <https://kurijn.github.io/#me>, <https://pietercolpaert.be/#me>; <br />
>     &nbsp;&nbsp;&nbsp;&nbsp;a <https://itskhaled.github.io/Person>

## Curl results

> 'C:\Users\Khaled\Desktop\ItsKhaled.github.io>curl -I https://itskhaled.github.io/' <br />
>> HTTP/1.1 200 OK <br />
>> Connection: keep-alive <br />
>> Content-Length: 2127 <br />
>> Server: GitHub.com <br />
>> Content-Type: text/html; charset=utf-8 <br />
>> permissions-policy: interest-cohort=() <br />
>> Last-Modified: Tue, 05 Mar 2024 21:14:56 GMT <br />
>> Access-Control-Allow-Origin: * <br />
>> Strict-Transport-Security: max-age=31556952 <br />
>> ETag: "65e78260-84f" <br />
>> expires: Tue, 05 Mar 2024 20:50:13 GMT <br />
>> Cache-Control: max-age=600 <br />
>> x-proxy-cache: MISS <br />
>> X-GitHub-Request-Id: A778:2AD818:D4FF2:D8D8F:65E78BDC <br />
>> Accept-Ranges: bytes <br />
>> Date: Tue, 05 Mar 2024 21:17:32 GMT <br />
>> Via: 1.1 varnish <br />
>> Age: 15 <br />
>> X-Served-By: cache-bru1480046-BRU <br />
>> X-Cache: HIT <br />
>> X-Cache-Hits: 1 <br />
>> X-Timer: S1709673453.669816,VS0,VE1 <br />
>> Vary: Accept-Encoding <br />
>> X-Fastly-Request-ID: cf1138215f6daef6acd1dba831e27d1d89aee9dc <br />

## Comments
While I don't have my own website, I can examine what features come with the GitHub page provided to me.

> 'C:\Users\Khaled\Desktop\ItsKhaled.github.io>curl -I https://itskhaled.github.io/' <br />

First, it is obvious that Github uses httpS, as they should.

> Cache-Control: max-age=600 <br />
> Age: 15 <br />
> X-Served-By: cache-bru1480046-BRU <br />
> X-Cache: HIT <br />
> X-Cache-Hits: 1 <br />

Here we can see that the page supports caching which can prevent the website from slowing down and keep loading, based on maximum page age.

> Access-Control-Allow-Origin: * <br />

Github also enables CORS by default, so a green flag for Linked Open Data :)

