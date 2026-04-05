      </tr>
        <tr>
          <td>Sejarah Islam</td>
          <td><span class="badge badge-green">Kategori</span></td>
          <td>Navbar – posisi 5</td>
          <td>Label deskriptif yang menjelaskan isi secara langsung tanpa jargon.</td>
          <td>sirah nabawi, sejarah islam</td>
        </tr>
        <tr>
          <td>Al-Quran & Hadis</td>
          <td><span class="badge badge-green">Kategori</span></td>
          <td>Navbar – posisi 6</td>
          <td>Dua sumber utama Islam digabung; pengguna tidak perlu mencari di dua tempat berbeda.</td>
          <td>tadabbur quran, hadis shahih</td>
        </tr>
        <tr>
          <td>Dakwah Digital</td>
          <td><span class="badge badge-green">Kategori</span></td>
          <td>Navbar – posisi 7</td>
          <td>Membedakan konten dakwah berbasis teknologi dari konten teks biasa.</td>
          <td>podcast islami, dakwah media sosial</td>
        </tr>
        <tr>
          <td>Tanya Ustaz</td>
          <td><span class="badge badge-gold">Fitur</span></td>
          <td>Navbar kanan (CTA)</td>
          <td>Label aksi yang mengundang interaksi, terasa personal dan mudah diingat.</td>
          <td>konsultasi islam, tanya jawab islam</td>
        </tr>
        <tr>
          <td>Tips Menjaga Lisan di Era Digital</td>
          <td><span class="badge badge-gold">Konten</span></td>
          <td>Di bawah Kategori Akhlak</td>
          <td>Judul spesifik yang menjawab kebutuhan nyata: bagaimana beretika di media sosial.</td>
          <td>menjaga lisan, etika media sosial Islam</td>
        </tr>
        <tr>
          <td>Kajian Terbaru</td>
          <td><span class="badge badge-gold">Fitur</span></td>
          <td>Footer / Sidebar</td>
          <td>Menunjukkan konten segar, mendorong pengguna kembali mengunjungi situs.</td>
          <td>kajian islam terbaru, ceramah online</td>
        </tr>
      </tbody>
    </table>

    <!-- Prinsip Labeling -->
    <div class="principles-grid">
      <div class="principle-card">
        <div class="p-num">PRINSIP 01</div>
        <div class="p-title">Jelas & Langsung</div>
        <div class="p-desc">Label tidak ambigu; pengguna langsung tahu isi halaman sebelum mengklik.</div>
      </div>
      <div class="principle-card">
        <div class="p-num">PRINSIP 02</div>
        <div class="p-title">Istilah Familiar</div>
        <div class="p-desc">Menggunakan kosakata Islam yang sudah dikenal, bukan terminologi teknis baru.</div>
      </div>
      <div class="principle-card">
        <div class="p-num">PRINSIP 03</div>
        <div class="p-title">Konsisten</div>
        <div class="p-desc">Gaya penulisan seragam di semua halaman: huruf kapital di awal kata tiap label.</div>
      </div>
      <div class="principle-card">
        <div class="p-num">PRINSIP 04</div>
        <div class="p-title">Ringkas</div>
        <div class="p-desc">Maksimal 3–4 kata per label menu agar nyaman dibaca di layar kecil (mobile).</div>
      </div>
    </div>

  </section>

  <!-- ══════════════════════════════════════════ -->
  <!-- TUGAS 3: RANCANG NAVIGASI / USER FLOW     -->
  <!-- ══════════════════════════════════════════ -->
  <section id="navigasi">
    <div class="section-num">Tugas 3</div>
    <h2 class="section-title">Rancangan Navigasi & User Flow</h2>
    <p class="section-desc">Alur pengguna (user flow) untuk menemukan konten "<strong>Tips Menjaga Lisan di Era Digital</strong>" yang berada di bawah kategori <strong>Akhlak</strong>.</p>

    <div class="flow-wrapper">
      <div class="flow-title">USER FLOW — Menemukan Konten "Tips Menjaga Lisan di Era Digital"</div>

      <div class="flow-diagram">

        <!-- Step 1 -->
        <div class="flow-node start">
          <div class="fn-label">🌐 Pengguna Membuka Website</div>
          <div class="fn-sub">Mengetik URL / klik link dari media sosial</div>
        </div>

        <div class="flow-arrow">
          <div class="arr-line"></div>
          <div class="arr-label">Halaman Beranda dimuat</div>
          <div class="arr-head"></div>
        </div>

        <!-- Step 2 -->
        <div class="flow-node">
          <div class="fn-label">🏠 Halaman Beranda (Home)</div>
          <div class="fn-sub">Melihat menu navigasi utama di bagian atas halaman</div>
        </div>

        <div class="flow-arrow">
          <div class="arr-line"></div>
          <div class="arr-label">Klik menu "Akhlak"</div>
          <div class="arr-head"></div>
        </div>

        <!-- Step 3 -->
        <div class="flow-node">
          <div class="fn-label">🌿 Halaman Kategori: Akhlak</div>
          <div class="fn-sub">Daftar semua artikel & sub-kategori Akhlak ditampilkan</div>
        </div>

        <!-- Dua opsi -->
        <div class="flow-arrow">
          <div class="arr-line"></div>
          <div class="arr-label">Pengguna memilih cara</div>
          <div class="arr-head"></div>
        </div>

        <!-- Dua jalur -->
        <div style="width:100%;max-width:480px;display:flex;gap:12px;">
          <div style="flex:1;display:flex;flex-direction:column;align-items:center;">
            <div class="flow-node" style="font-size:13px;padding:10px 14px;text-align:center;width:100%">
              <div class="fn-label" style="font-size:13px;">🔍 Jalur A: Cari Manual</div>
              <div class="fn-sub">Scroll halaman, cari artikel di daftar</div>
            </div>
          </div>
          <div style="flex:1;display:flex;flex-direction:column;align-items:center;">
            <div class="flow-node" style="font-size:13px;padding:10px 14px;text-align:center;width:100%">
              <div class="fn-label" style="font-size:13px;">🔎 Jalur B: Gunakan Search</div>
              <div class="fn-sub">Ketik kata kunci di kotak pencarian</div>
            </div>
          </div>
        </div>

        <div class="flow-arrow">
          <div class="arr-line"></div>
          <div class="arr-label">Kedua jalur menuju artikel yang sama</div>
          <div class="arr-head"></div>
        </div>

        <!-- Step 4 -->
        <div class="flow-node highlight">
          <div class="fn-label">📄 Artikel: "Tips Menjaga Lisan di Era Digital"</div>
          <div class="fn-sub">Konten lengkap terbuka — Sub-kategori: Akhlak di Era Digital</div>
        </div>

        <div class="flow-arrow">
          <div class="arr-line"></div>
          <div class="arr-label">Selesai membaca</div>
          <div class="arr-head"></div>
        </div>

        <!-- Step 5 -->
        <div class="flow-node end">
          <div class="fn-label">✅ Rekomendasi Konten Terkait</div>
          <div class="fn-sub">Sistem menampilkan artikel lain di kategori Akhlak yang relevan</div>
        </div>

      </div><!-- /flow-diagram -->
    </div><!-- /flow-wrapper -->

    <!-- Breadcrumb Visual -->
    <h3 style="font-family:'Lora',serif;font-size:1.05rem;color:var(--green-dark);margin:36px 0 12px;">Breadcrumb Navigasi</h3>
    <div style="background:white;border:1px solid var(--border);border-radius:10px;padding:18px 24px;display:flex;align-items:center;flex-wrap:wrap;gap:6px;font-size:14px;">
      <span style="color:var(--green-mid);font-weight:500;cursor:pointer;">Beranda</span>
      <span style="color:var(--text-light);">›</span>
      <span style="color:var(--green-mid);font-weight:500;cursor:pointer;">Akhlak</span>
      <span style="color:var(--text-light);">›</span>
      <span style="color:var(--green-mid);font-weight:500;cursor:pointer;">Akhlak di Era Digital</span>
      <span style="color:var(--text-light);">›</span>
      <span style="color:var(--text-dark);font-weight:600;">Tips Menjaga Lisan di Era Digital</span>
    </div>
    <p style="font-size:12.5px;color:var(--text-light);margin-top:8px;">Breadcrumb menampilkan posisi pengguna dalam hierarki website sehingga mudah kembali ke halaman sebelumnya.</p>

    <!-- Prinsip navigasi -->
    <h3 style="font-family:'Lora',serif;font-size:1.05rem;color:var(--green-dark);margin:36px 0 16px;">Prinsip Rancangan Navigasi</h3>
    <div class="principles-grid">
      <div class="principle-card">
        <div class="p-num">NAV 01</div>
        <div class="p-title">Maksimal 3 Klik</div>
        <div class="p-desc">Pengguna dapat menemukan konten apapun dalam maksimal 3 kali klik dari beranda.</div>
      </div>
      <div class="principle-card">
        <div class="p-num">NAV 02</div>
        <div class="p-title">Breadcrumb Selalu Tampil</div>
        <div class="p-desc">Breadcrumb di setiap halaman membantu pengguna mengetahui posisi mereka.</div>
      </div>
      <div class="principle-card">
        <div class="p-num">NAV 03</div>
        <div class="p-title">Search Terintegrasi</div>
        <div class="p-desc">Kotak pencarian selalu ada di navbar sehingga jalur alternatif selalu tersedia.</div>
      </div>
      <div class="principle-card">
        <div class="p-num">NAV 04</div>
        <div class="p-title">Konten Terkait</div>
        <div class="p-desc">Setiap artikel menampilkan rekomendasi artikel terkait untuk memperpanjang sesi belajar.</div>
      </div>
      <div class="principle-card">
        <div class="p-num">NAV 05</div>
        <div class="p-title">Mobile-Friendly</div>
        <div class="p-desc">Menu navigasi responsif — berubah menjadi hamburger menu di perangkat mobile.</div>
      </div>
      <div class="principle-card">
        <div class="p-num">NAV 06</div>
        <div class="p-title">Highlight Aktif</div>
        <div class="p-desc">Menu kategori aktif ditandai secara visual sehingga pengguna tahu sedang di mana.</div>
      </div>
    </div>

  </section>

</main>

<!-- FOOTER -->
<footer>
  <div style="margin-bottom:8px;">
    <strong>Website Dakwah KPI</strong> — Arsitektur Informasi
  </div>
  <div>Tugas Kelompok · Dakwah Mahasiswa KPI · UIN Sunan Ampel Surabaya</div>
  <div style="margin-top:10px;font-size:12px;opacity:0.6;">"Sampaikan dariku walau satu ayat." — HR. Bukhari</div>
</footer>

</body>
</html>
