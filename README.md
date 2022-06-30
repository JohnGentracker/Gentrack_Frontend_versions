# Gentrack_Frontend_versions
Trial of Frontend auto updater

### This repository is used to store data regarding the frontend versions of Assurance Websites.

### It purely contains json files that are automatically updated when the node.js function is run; this is read as an endpoint using badge.io and then displayed on confluence to represent the frontend version of all the Assurance sites automatically.

![Custom badge](https://img.shields.io/endpoint?color=gree&label=Frontend%20Version&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAQUAAAEjCAYAAAA7YxS6AAAAAXNSR0IArs4c6QAAFkZJREFUeF7tnU2vZUUVhqv2%2FRWaGBtD6AgJEYfCkPZjZGhGBuIAExwIEzBOgMQEmBibiTrQRAYGwog2jlSaIe3QNiRo6BBpY2L%2FA2e3ytTtvWHf47nn1K6qVbWq3rdH0F2f71r17FWrau9jDf9QASpABVYKWKpBBagAFVgrQCjQH6gAFTinAKFAh6ACVIBQoA9QASpwsQKMFOgdVIAKMFKgD1ABKsBIgT5ABahApALcPkQKxWJUAEUBQgHF0pwnFYhUgFCIFIrFqACKAoQCiqU5TyoQqQChECkUi1EBFAUIBRRLc55UIFIBQiFSKBajAigKEAooluY8qUCkAoRCpFAsRgVQFCAUUCzNeVKBSAUIhUihWIwKoChAKKBYmvOkApEKEAqRQrEYFUBRgFBAsTTnSQUiFSAUIoViMSqAogChgGJpzpMKRCpAKEQKVaqY9%2F7STluPGGNuLX9nrb1Tqq%2Fe2tmjzbkpIGtT05aEQkG1Z6cOi%2FxB59xXQ9PW2gfnLsLfb%2F1zy3v%2F91BpmqZ%2FGGPCf9%2FqdXF475%2BYBTjTJ1eb0FbQZ6VN%2BKtu9dnqHFLlCYVEZWcAPLVy7pRFn9j7WbXg%2FO8GUFhrf5%2FTkETd1vp4798eAaQStjnWJqFwTKH53xcn994%2FaYypDYCYUTaFxBIlOeeetNY%2BFTPgymXOoq5pmt7VCNHKWhzsjlA4IE8IdxU7%2BUHDzk9K0QXQASgPabRA9O1et2NSICEUdpTtGQQXOYm19mVjTDHnDxp5719RGjGlrBUCYqUaoXAvWRVOBJ5SvDVIcfR9dYLzv5oSPq80eq3UYDS2UyPC0jjv9ZigoRAc3Tn3mtI9sKTvBDhcjQ2bvfcvee%2BHhsEesZMBKmm4Gm1DQmHA8DfaV%2BYn4cuxQFgaRtYsbL%2Bsta9Hi9x5QSgojJgviPW%2FVBjstk84jA8HCCgAbxNCviSc12%2BODI7BhnAYFw5DQwElOXbBAq6yJwbNNwTJq%2Bh7DM4S%2Fz4sFOYn2XUJ0bS3WXsPHODrvQ9aa7zUJWouqUhMdNBHGh8OCtwqlN8qxDooOIjDaY666%2Baxthv2SBLcKVVkyJGjhnlLEX3Um7Jga9QZJlI4PT19C%2FC%2BwbK3VeeIwLmG8GZs11FD91BgFlxvFhw5agi5hpOTk6drPNlL99E1FMC3C108jZBzPL1uJ7qFArcLfX2hCdxeSe%2BblI4AYtvrDgp88sS%2FsxDrBLXKMbLr43SiKyhwj9rnHnUNHXAwqDghOvYQ6AYKBEL%2FQFi9XAV72an2xbJjANj3711AARkIPThRiuMh21T7yYR6KMzO82mK4%2FVeZ1QgMGI4%2B7CP2iNL1VAgEPTeQSgFXEYM%2BraFaqGA7CyjRwi7QKGtdcFfJRSQnURzWFkqOtjXDqNCPWBQCQXn3F9RX8Pt9WpsCWCAg0HNDVV1UEC9%2BYYaIezZSoTPx6N%2BB%2BO%2Brd%2FOLAHj3TZUQQH4zbpb0zR9XcLAPbYJ7AfhDcvmYFADBfCbbs0dQRs8UCPG8BJV6weECihwL9nHnfja4EDNLbU%2BfVIBBRq%2F9nLroz8%2BLNo8LJpDAXj%2F2DxM7AEN3FbWf0W%2BKRRo8PoG7wEEu2NEzS%2B0OpFqCgXgbYOaM%2BleIAHsK9Vft24GBdK%2Fl%2BWoY5yMKutFlU2gAJ5A4vFjImdQ80%2B1txFNoAAcCnLbkAiEpRp9J1PAiOrVoYBKew2XUiL8QX0R4G1EtdOq6lBwznn1nicwQA3XVwWm1aRJ1HxUrUtNVaGAGiXU3hM2WakVO2VOSjbpWA0KNKSsISuuSRVdoT5gakQLNaHwkvf%2BNRUeVXEQNYxYcTqquuJWVMYcVaCAHCVM01RFYxn30N0qowUZ%2B1RxWBpPxnhs1RhGC%2BW9QBwKjBLKG40tfq4AHzjlvaEGFJhLKG83trhSADVakNqaikPBOXfLGPM1NC%2BWMhiajjHzBY4WRG7IikIB9fYZ7yXELOVyZYC3qH%2BbpumRckrea0kUCsA3z%2FjSU2lPPdIesK8VjxbEoEB6V14V4N0xKi3nAJJQQE0wFid3OXOP3RLzV2XsKwYFGqiMgdhKvAJMOMZrdaikCBRQtw5MMJZxytRW6Hepyp2vJwUFbh3K2IetbFSAEepGwfYUF4ECDZNvGLaQpgC3EGm6rWsVhwJDuHyjsIV0Beh%2F6dotNSWgwK1Dvl3YQoYCjFQzxJO4vESD5BmEtfMV4BYiT8PikQLiyyk8dchzwtK1UbcQpT7oUxQKqLfKShmj9OJAbg%2Fx4WSMKfIuRGkooOYT%2BK6DMgKhvgtR4u3colBgPkHZygAeDvMK6cYvDQW433RgPiHd%2BSRrMq%2BQrm4xKNAI6UZgTRkFEPMKJR5SJaHwhPf%2Buox59bbKX37SaxvQ7Wx2srEkFJhk1Ls%2BIEeGmlfITTYWgwKpDLnuVE8a%2BIg86zSMUMhz6%2BxQLa971j6kAHCeK%2BtDPyWhAHfywEtL%2BqGEmGzM9csiUCCR9S8O1BEibmtzTyBKQYEnD6irTvm8EaGQe925FBR48qB8caAO7%2FT09BfW2ufQ5p9zAkEoZHhLjvAZ3bLqBgV4LLlBrLloESiAvnzCk4ft%2Fla9Bo8lt0teBArOuQ%2BMMY9u777rGoRCB%2BYDhsIVa%2B37KSYqBQW4H5HNzfCmGIt1tivAk7HtmhEK2zU7q%2BG9%2F%2BXJycnzidVZrZIChMJ2oUtBgReXtmvPGpUU4AWmbUITCtv0%2Bqx07q2xxG5ZLUEBQmGbaITCNr0IhUS9WlYjFLapTyhs04tQSNSrZTVEKOTkvLKhwEROS3dn3zEKIF51JhRiPKNwGWtt1uuphYfD5g4oQChscw9GCtv0Wm8fCIVE7WpXA4XC2ycnJ0%2BnaE0opKgWfm%2BPkUKicvWrgUIh%2BR5NNhSCiRETOTySrL%2B4U3tE9M%2BmOQVCIdVVWa%2BWAohQyHloMVJI9Mwc0RO7ZLVEBRChwEgh0VlyquWIntMv625XABEKOQ8tRgrbfeysBqGQKFyDaqBQSD4dKwUFxFenk7O7DdYFbJe8XLfd9KWggPiRlZvTND22XXLWqKmA9%2F5x7%2F2Nmn1q6Mta2%2FwjK4hQ4JeXNHj%2FkTEAf3kp%2BVeiikQK%2FGJuB6sDdIioH27N%2BeHjIlBAFZ5fc9ZPGj6wttuoFBT4YzDbtWeNCgqAQiFra1sKCkzmVHBwdrFdAdAvjWclwUtB4ZL3%2FtPtJuu7Rs4Fkb5n3s%2FoEe8o5N6hKQKF4CIUv5%2BFgjJS4DsKL1trX0%2B1c0koIB5LZoVpqUZjvTgFeEchTqfdUsWgAJrQMTyBSHO8GrVQT8VyjiODXYpBgQao4ebsY4sCfFBtUevzsiWhgHoCkfziSZrJWCtWAZ48xCp1vlwxKDDZmGYA1pJTgMnvNG1LQ4HJxjQ7sFZhBYDfeciOXItCgXu4wp7N5pIVQPXF3CRj0URjaAyYzsmvqSZ7PSseVID5hHQHKRopoF4Wyb1Blm4%2B1rxIAeYT0n2jKBTmZCPzCun2YM0CCgBfWsrOJxTfPoQGuZcr4NVsIksB%2BmCWfOUuLy3DAM4rFKF0njlZe45WPaASxa7cF98%2B0CiA7qhoysBbh6yXoNYmFIECwzdFqwRsKPS9fIOLQIFbiHzDsIU0BXgUmaabeKSAejRpjCm2r8s3LV4LqFuH0kfiIpECTyHsHbwl2X7G3DqUsYEYFEjtMgZiK%2FEKIF5YkohOxaDAU4h4Z2bJfAW89y9476%2Flt9RXC9baF621b5QctSgUgMM53lko6aURbYEmGEW%2B%2FCUKBSYcI7yZRbIV4FY1W8JzDYhCgQlHJhzLuuv%2B1oAj0uTfizxkF3EokOI1lgVuH4xGy9teHApzwhHxzUlT4oMX5U0%2BVovAUYLYNzyqQIHRwlgLUctsGCXIWKIKFBgtMLcg4b6MEiRULfi7D8eGx2jhmEL89y0KMErYota2stUiBUYLjBa2uebh0owSSqp5vq2qUECNFiSuosq5hP6W6UeyNqoKBfBoQSxbLOsi%2BlpHvb1Y6zSrOhSA94K3p2m6rG%2BJ9TUi1HccSr8e3fTy0r7OUfeDNQ3b11KPHy3om5BV77xUjxQW8zvnPjbGPBDvDmOUrBUCjqHW%2BVmgPkystVW3ns2gwGTRiMtWbk70Fzltd1tuBoUwEFTycxuxzcHnPNSfGVlu0y21dFMozKcR3EakWg%2BkHurDQ%2BIDKjEu0xwKwGEhTyMiPBTYP5p9BLg5FLiNOHk%2BYm1AFkE%2BvrbWfsvaNrdgVUAB%2FFJT8W%2FsjUIQ4BOqqqcNqhKN68EwmdTmqaAVIKi3FjUkodVECsE5GS4SDLMfQH6ZWQMQgv6qoDA7xOPe%2Bxtan2CC42qWWBKc0%2BamgROLahLP6qDAxCNu4hEZCC0Ti2pzCrsDQz2b1hJCbn7EZ1YA3jpWfa8hxkwqI4Vl4ARDjAn7LwOeZG560rDPe1RDgUeVZX8OTCM%2BCAT7vja7qIcCwTAuGAgEfUBQefpwETWdc%2B8ZY65oo6r0eEbNMRAIOoHQFRTmiIFgkKZQhfYJBL1A6A4KPK7s%2F7hyPnb8FeBr0Lc1HTseYn8XOYXdCaB%2Bp88Yc8Na%2B2yrF2VygwjeQ%2BjjxmqXUAC%2F%2BdjNE2cNEdTj5R5B3i0UZjBc8t6jfpFH3fk2k8TnFeg1Sdw1FFZg%2BA3iyUSrL%2FPEbiOYUNSdULzIjt1DYZkY96u69qu0hy57xIK8y9OHQ5Pjk6n9k2m2ASO3LatQWdlhIoW1rqinE2EPO03TtVanEzxu7Dc6WK%2BfIaEAnoQMpxO%2Ftrbe9WhGB%2FW0rhFUDAuFnVwD6mWZH1kru6VAjcp6PGqMBcrwUFiiBudc%2BEDqc7HCjFJOaksBvlUQh21L%2F4OAwipquEQ45O17Zxj8BPAIOGzLhobBsk6goEA4mPCVn6RPyhMGstuwlpHBbt%2BQUFjDwRhz1Xt%2FTZNRKoxl01Vp0LxBeM%2FkZ9I5mQq23twFNBR2jjHDV6RHD4uTQ%2BBwwoCw9ZLKwWxemQ0rEAo74q%2Bc%2F5ujvN47O%2FofSj315sjh2wPlFWCjgn3sIRQOEDnso51z37XWdgcI7%2F2b0zS9UwoE%2B2QKAJ23Xz%2FsEKABBH8yxlxvddmrYTBwsGtCIdIyqwWg9Ql523v%2F3jRNxSKCSGnOilGfLWrpLksoJNpnWQTOuYestY81eFLe8N5%2FHCBgjPlE29MuRFnGmIe99wGiX66sz21jzL%2FmSOBDjfokul2VaoRCQZlnUNwfFoNz7j5r7eXMBXHm3N77f0%2FT9JExplsHP6BNsMADCWb4TBtjzH%2Bnafq0Z30S5i9WhVAQk%2Fb%2FG54XxvIPAR7rP58s%2F6PtqV9DImpTQ%2BW4PgiFOJ1YigrAKEAowJiaE6UCcQoQCnE6sRQVgFGAUIAxNSdKBeIUIBTidGIpKgCjAKEAY2pOlArEKUAoxOnEUlQARgFCAcbUnCgViFOAUIjTiaWoAIwChAKMqTlRKhCnAKEQpxNLUQEYBQgFGFNzolQgTgFCIU4nlqICMAoQCjCm5kSpQJwChEKcTixFBWAUIBRgTM2JUoE4BQiFOJ1YigrAKEAowJiaE6UCcQoQCnE6sRQVgFGAUIAxNSdKBeIUIBTidGIpKgCjAKEAY2pOlArEKUAoxOnEUlQARoEmUDg9Pf2ttfZLI6tsrX0W8fcbWth09YO3Lbqv0mf4tStr7Rs1OmsJhWdqTLBVH9baF2sZsdUctfTrnPuPMeYLWsYjMQ5r7RXJHwtej7kJFMLvDHrvb0iIp6jNG9M0hV%2Br5h9BBcIvS3nvw0%2FGDf1nmqZqa7VaR7sWc875oa1ojKlpyNG1vGh%2B89bh2uDzr%2FqAaQmF94wxV0Y2Zs2Qb2QdD83NOfeBMebRkedfeyvaDAok%2FMhuXGduKFsHa234BfM7dVQ1piUUIPaCtQ1ay3E09MMHi4wVmkEhTGc%2BmuQphIxth2%2BVpw4yJm4KBZBTiJvTND0mYz7cVkF85%2B40TV%2BsbeWmUAiTBUkUVTtjru1ArfpzziEkqpvcdWkOBYR9off%2BzZOTkx%2B0WkCj9csEo6xFNUCBCUdZGw%2FXOsKDxBhT9W7C2kmaQ4EJx%2BHWrPiEEC6%2BtbzjogIKDAfF19EwHYBECU2T0yqgwGhhmDUrPhEeQ4pL3O7y0u7UQKKFu9bab9S8nSbvQvV6YJRQR2s1kQJKtMCTiHTHZpSQrt2WmqqgABItGF593uKi98oyStiuWWoNVVBAMT6jhW3uCvSwUHHJTR0UgrvwluO2RTN6aYR3ZDQ9KFRCgffaR1%2Fm8fOjL8RrVaqkSiigJB1rfzyjlNPUbIfJxZpq3%2BtLLRTmfeRfAD7IWfUDGvVdLL1HhG1Dy%2BvMF1lGLRTmpCPCB16bvB6bvlTr1ETZNmi8t6IaCijbCE1JpjpL%2Fngv3DYc10iqhHoo8DRCyvR620XYNmh%2BEHQBBZD8Aq9A85KSClJ3AQWg%2FELTt%2BNaeyTzCK0toPz0YZ88CFddNYeVki4LEg2GK%2B4qbi0esmU3kcIyCYT9JuL9Bd5ilUTutra7g8KceET4aKf6J8o2V7u4NEFfSsky7XQJBZ5IlDG%2BhlYQgNDblrBbKMx70LcG%2Fx3BcCLx%2FVo%2FQV4bEswR1VY8rr9uoTCfSIQvQRMMcbZWVYpAUGWOc4PpGgrLTACSVENFDASCXiCEkQ0BBZAcwxBgIBB0A2EoKICAoYtz7ovcHiGpOMJx8jCRwuKICE%2BiHh0PBAhDHCMPB4U5AfmC9%2F6a%2FkAtfYS9HHPxlCjdxq1qDgmFGQzhWwy%2FG%2FwjLTettU9r%2FR2J%2BV0G2qDV6k7sd1goLHoAhK0qE5DcxiWuSAXVhofCajvx45GjBi15hrBdcM69Yq19RoF%2FSw1BJYhLTRYCCkAXnZpuJxC2C73kcnIAAQOFndOJkaOG8BT7ubX2jRzH2FqX27StiuktDweFJWoACHGrRA0A0UETyLZEBiQUVlHD8O9OhHB3mqZXS59QIBw1SmnXcsHH9A0NhRUcwvHlTwd%2B47LY0w4hkTjD4J1R3049BgZCYaXQHAoTDnu8BggGxaOqY4tQ278TCvsXAELkEP2dhtHvHKBuEy6CEaFwANPh6WiMueq9H%2Ba0InUBhCjKOfe9ge4fhETs9dqnNNqign3jIRQirdT5ojhbAMaYsAjuRE55b7HOQXnXe%2F9HicRrjqba6hIKCRZZAeI7im9JniUXS4DgIok60WEB4oeoicOtLk4obFVsp%2Fzy5HTOPWStbQmJ5Sn4kSQIDgBi2WpdNcZ8pSEsb3rvP56mqYkOme6kojqhUNgMMyTuN8Y87L2XWiB3jTH%2F1Oz8O7C8LASKNQAYCRTyZUKhkJDHmlnDIpQNkcVuHWvt5bDQ138%2FP%2FHCX304%2F%2F0nuXmBY2OV%2BvddDXZ1CPMPf3dMA24DpCx0r11CQVZftk4FulOAUOjOZBwwFZBVgFCQ1ZetU4HuFCAUujMZB0wFZBUgFGT1ZetUoDsFCIXuTMYBUwFZBQgFWX3ZOhXoTgFCoTuTccBUQFYBQkFWX7ZOBbpTgFDozmQcMBWQVYBQkNWXrVOB7hQgFLozGQdMBWQVIBRk9WXrVKA7BQiF7kzGAVMBWQUIBVl92ToV6E4BQqE7k3HAVEBWAUJBVl%2B2TgW6U4BQ6M5kHDAVkFXgfwO30ucyL3t7AAAAAElFTkSuQmCC&logoColor=white&style=plastic&url=https%3A%2F%2Fraw.githubusercontent.com%2FJohnGentracker%2FGentrack_Frontend_versions%2Fmain%2FUS007-1.json)

* A typical HTML string to create a badge looks like this:

https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/JohnGentracker/Gentrack_Frontend_versions/main/US007-1.json&style=plastic&logo=data:image/png;base64,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