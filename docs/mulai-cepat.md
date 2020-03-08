# Mulai cepat

Check the [README.MD](https://github.com/chlasswg26/grabutxxi) for how to install GrabutXXI.

## Method

> Default Method : GET

## latest.php

> Show Latest Movies Update

<table>
  <thead>
    <tr>
      <th style="text-align:left">Required</th>
      <th style="text-align:left">Optional</th>
      <th style="text-align:left">Value</th>
      <th style="text-align:left">Example</th>
      <th style="text-align:left">Description</th>
      <th style="text-align:left">Result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"><code>page</code>
      </td>
      <td style="text-align:left"><code>page</code> = Number to page <code>(1,2,3,4,5 or more)</code>
      </td>
      <td style="text-align:left">
        <p>Required : <a href="https://yourdomain.com/latest.php">https://yourdomain.com/latest.php</a>
        </p>
        <p>Optional : <a href="https://yourdomain.com/latest.php?page=2">https://yourdomain.com/latest.php?page=2</a>
        </p>
      </td>
      <td style="text-align:left">
        <p>Results returning array of json encode</p>
        <p>Use <code>&apos;code&apos;</code> for request <b><code>post.php</code></b>
        </p>
      </td>
      <td style="text-align:left">
        <p><code>isPaging</code> = Boolean (true / false)
          <br /> <code>next</code> = Number to next page (1,2,3,4,5 or more if available)
          <br
          /> <code>prev</code> = Number to previous page (1,2,3,4,5 or more if available)</p>
        <p> <code>code</code> = String of Base64Encode
          <br /> <code>title</code> = String
          <br /> <code>image</code> = String of Image to Base64Encode (Long character)</p>
      </td>
    </tr>
  </tbody>
</table>## popular.php

> Show Popular Movies all the age

<table>
  <thead>
    <tr>
      <th style="text-align:left">Required</th>
      <th style="text-align:left">Optional</th>
      <th style="text-align:left">Value</th>
      <th style="text-align:left">Example</th>
      <th style="text-align:left">Description</th>
      <th style="text-align:left">Result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Required : <a href="https://yourdomain.com/popular.php">https://yourdomain.com/popular.php</a>
      </td>
      <td style="text-align:left">
        <p>Results returning array of json encode</p>
        <p>Use <code>&apos;code&apos;</code> for request <b><code>post.php</code></b>
        </p>
      </td>
      <td style="text-align:left"><code>code</code> = String of Base64Encode
        <br /> <code>title</code> = String
        <br /> <code>image</code> = String of Image to Base64Encode (Long character)</td>
    </tr>
  </tbody>
</table>## archive.php

> Show Archive Movies Playlist

<table>
  <thead>
    <tr>
      <th style="text-align:left">Required</th>
      <th style="text-align:left">Optional</th>
      <th style="text-align:left">Value</th>
      <th style="text-align:left">Example</th>
      <th style="text-align:left">Description</th>
      <th style="text-align:left">Result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Required : <a href="https://yourdomain.com/archive.php">https://yourdomain.com/archive.php</a>
      </td>
      <td style="text-align:left">
        <p>Results returning array of json encode</p>
        <p>Use <code>&apos;code&apos;</code> for request <b><code>playlist.php</code></b>
        </p>
      </td>
      <td style="text-align:left"><code>code</code> = String of Base64Encode
        <br /> <code>image</code> = String of Image to Base64Encode (Long character)</td>
    </tr>
  </tbody>
</table>## search.php

> Search Movies Update

<table>
  <thead>
    <tr>
      <th style="text-align:left">Required</th>
      <th style="text-align:left">Optional</th>
      <th style="text-align:left">Value</th>
      <th style="text-align:left">Example</th>
      <th style="text-align:left">Description</th>
      <th style="text-align:left">Result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><code>query</code>
      </td>
      <td style="text-align:left"><code>page</code>
      </td>
      <td style="text-align:left">
        <p><code>query</code> = String to search by query <code>(superman / the lord of the rings)</code>
        </p>
        <p> <code>page</code> = Number to page <code>(1,2,3,4,5 or more)</code>
        </p>
      </td>
      <td style="text-align:left">
        <p>Required : <a href="https://yourdomain.com/search.php?query=batman">https://yourdomain.com/search.php?query=batman</a>
        </p>
        <p>Optional : <a href="https://yourdomain.com/latest.php?query=batman&amp;page=2">https://yourdomain.com/latest.php?query=batman&amp;page=2</a>
        </p>
      </td>
      <td style="text-align:left">
        <p>Results returning array of json encode</p>
        <p>Use <code>&apos;code&apos;</code> for request <b><code>post.php</code></b>
        </p>
      </td>
      <td style="text-align:left">
        <p><code>isPaging</code> = Boolean (true / false)
          <br /> <code>next</code> = Number to next page (1,2,3,4,5 or more if available)
          <br
          /> <code>prev</code> = Number to previous page (1,2,3,4,5 or more if available)</p>
        <p> <code>code</code> = String of Base64Encode
          <br /> <code>title</code> = String
          <br /> <code>image</code> = String of Image to Base64Encode (Long character)</p>
      </td>
    </tr>
  </tbody>
</table>## playlist.php

> Show Movies Playlist

<table>
  <thead>
    <tr>
      <th style="text-align:left">Required</th>
      <th style="text-align:left">Optional</th>
      <th style="text-align:left">Value</th>
      <th style="text-align:left">Example</th>
      <th style="text-align:left">Description</th>
      <th style="text-align:left">Result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><code>code</code>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"><code>code</code> = String to fetch playlist data by query <code>code</code>
      </td>
      <td style="text-align:left">Required : <a href="https://yourdomain.com/playlist.php?query=">https://yourdomain.com/playlist.php?query=</a><code>code</code>
      </td>
      <td style="text-align:left">
        <p>Results returning array of json encode</p>
        <p>Use <code>&apos;code&apos;</code> for request <b><code>post.php</code></b>
        </p>
      </td>
      <td style="text-align:left"><code>code</code> = String of Base64Encode
        <br /> <code>title</code> = String
        <br /> <code>image</code> = String of Image to Base64Encode (Long character)</td>
    </tr>
  </tbody>
</table>## getGenre.php

> Show Movie Genre Codes \(to bypass real genres use Base64Decode\)

<table>
  <thead>
    <tr>
      <th style="text-align:left">Required</th>
      <th style="text-align:left">Optional</th>
      <th style="text-align:left">Value</th>
      <th style="text-align:left">Example</th>
      <th style="text-align:left">Description</th>
      <th style="text-align:left">Result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Required : <a href="https://yourdomain.com/getGenre.php">https://yourdomain.com/getGenre.php</a>
      </td>
      <td style="text-align:left">
        <p>Results returning array of json encode</p>
        <p>Use <code>&apos;code&apos;</code> for request <b><code>genre.php</code></b>
        </p>
      </td>
      <td style="text-align:left"><code>code</code> = String of Base64Encode</td>
    </tr>
  </tbody>
</table>## getCountry.php

> Show Movie Country Codes \(to bypass real countrys use Base64Decode\)

<table>
  <thead>
    <tr>
      <th style="text-align:left">Required</th>
      <th style="text-align:left">Optional</th>
      <th style="text-align:left">Value</th>
      <th style="text-align:left">Example</th>
      <th style="text-align:left">Description</th>
      <th style="text-align:left">Result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Required : <a href="https://yourdomain.com/getCountry.php">https://yourdomain.com/getCountry.php</a>
      </td>
      <td style="text-align:left">
        <p>Results returning array of json encode</p>
        <p>Use <code>&apos;code&apos;</code> for request <b><code>country.php</code></b>
        </p>
      </td>
      <td style="text-align:left"><code>code</code> = String of Base64Encode</td>
    </tr>
  </tbody>
</table>## genre.php

> Show Movies by Genre

<table>
  <thead>
    <tr>
      <th style="text-align:left">Required</th>
      <th style="text-align:left">Optional</th>
      <th style="text-align:left">Value</th>
      <th style="text-align:left">Example</th>
      <th style="text-align:left">Description</th>
      <th style="text-align:left">Result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><code>query</code>
      </td>
      <td style="text-align:left"><code>page</code>
      </td>
      <td style="text-align:left">
        <p><code>query</code> = String to fetch genre by query <code>code</code>
        </p>
        <p> <code>page</code> = Number to page <code>(1,2,3,4,5 or more)</code>
        </p>
      </td>
      <td style="text-align:left">
        <p>Required : <a href="https://yourdomain.com/genre.php?query=">https://yourdomain.com/genre.php?query=</a><code>code</code>
        </p>
        <p>Optional : <a href="https://yourdomain.com/genre.php?query=">https://yourdomain.com/genre.php?query=</a><code>code</code>&amp;page=2</p>
      </td>
      <td style="text-align:left">
        <p>Results returning array of json encode</p>
        <p>Use <code>&apos;code&apos;</code> for request <b><code>post.php</code></b>
        </p>
      </td>
      <td style="text-align:left">
        <p><code>isPaging</code> = Boolean (true / false)
          <br /> <code>next</code> = Number to next page (1,2,3,4,5 or more if available)
          <br
          /> <code>prev</code> = Number to previous page (1,2,3,4,5 or more if available)</p>
        <p> <code>code</code> = String of Base64Encode
          <br /> <code>title</code> = String
          <br /> <code>image</code> = String of Image to Base64Encode (Long character)</p>
      </td>
    </tr>
  </tbody>
</table>## country.php

> Show Movies by Country

<table>
  <thead>
    <tr>
      <th style="text-align:left">Required</th>
      <th style="text-align:left">Optional</th>
      <th style="text-align:left">Value</th>
      <th style="text-align:left">Example</th>
      <th style="text-align:left">Description</th>
      <th style="text-align:left">Result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><code>query</code>
      </td>
      <td style="text-align:left"><code>page</code>
      </td>
      <td style="text-align:left">
        <p><code>query</code> = String to fetch genre by query <code>code</code>
        </p>
        <p> <code>page</code> = Number to page <code>(1,2,3,4,5 or more)</code>
        </p>
      </td>
      <td style="text-align:left">
        <p>Required : <a href="https://yourdomain.com/country.php?query=">https://yourdomain.com/country.php?query=</a><code>code</code>
        </p>
        <p>Optional : <a href="https://yourdomain.com/country.php?query=">https://yourdomain.com/country.php?query=</a><code>code</code>&amp;page=2</p>
      </td>
      <td style="text-align:left">
        <p>Results returning array of json encode</p>
        <p>Use <code>&apos;code&apos;</code> for request <b><code>post.php</code></b>
        </p>
      </td>
      <td style="text-align:left">
        <p><code>isPaging</code> = Boolean (true / false)
          <br /> <code>next</code> = Number to next page (1,2,3,4,5 or more if available)
          <br
          /> <code>prev</code> = Number to previous page (1,2,3,4,5 or more if available)</p>
        <p> <code>code</code> = String of Base64Encode
          <br /> <code>title</code> = String
          <br /> <code>image</code> = String of Image to Base64Encode (Long character)</p>
      </td>
    </tr>
  </tbody>
</table>