# 📖 RF & Wireless Interview Test - Part I Answers
## RF Fundamentals & Measurement (Q1-Q20)

---

### Q1. Power Level Conversion
**Question:** Convert 30 dBm to watts.
**Options:**
- a) 0.001 W
- b) 0.01 W  
- c) 0.1 W
- d) 1 W

**Answer:** d) 1 W

**Question Explanation (English):** This question tests understanding of dBm to watt conversion using the formula P(watts) = 10^(dBm/10) × 0.001.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra khả năng chuyển đổi từ đơn vị dBm sang watt sử dụng công thức P(watts) = 10^(dBm/10) × 0.001.

**Answer Explanation (English):** 30 dBm = 10^(30/10) × 0.001 = 10^3 × 0.001 = 1000 × 0.001 = 1 W. The formula converts dBm (decibels relative to 1 milliwatt) to absolute power in watts.

**Giải thích đáp án (Tiếng Việt):** 30 dBm = 10^(30/10) × 0.001 = 10^3 × 0.001 = 1000 × 0.001 = 1 W. Công thức chuyển đổi từ dBm (decibel so với 1 milliwatt) sang công suất tuyệt đối tính bằng watt.

---

### Q2. Voltage Gain in dB
**Question:** If input voltage is 1V and output voltage is 10V, what is the voltage gain in dB?
**Options:**
- a) 10 dB
- b) 20 dB
- c) 30 dB
- d) 40 dB

**Answer:** b) 20 dB

**Question Explanation (English):** This question tests understanding of voltage gain calculation in decibels using the formula Gain(dB) = 20 × log₁₀(Vout/Vin).

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra khả năng tính toán độ lợi điện áp theo đơn vị decibel sử dụng công thức Gain(dB) = 20 × log₁₀(Vout/Vin).

**Answer Explanation (English):** Voltage gain = 20 × log₁₀(10V/1V) = 20 × log₁₀(10) = 20 × 1 = 20 dB. The factor of 20 is used for voltage ratios (not 10 for power ratios).

**Giải thích đáp án (Tiếng Việt):** Độ lợi điện áp = 20 × log₁₀(10V/1V) = 20 × log₁₀(10) = 20 × 1 = 20 dB. Hệ số 20 được sử dụng cho tỷ số điện áp (không phải 10 cho tỷ số công suất).

---

### Q3. Power Attenuation
**Question:** A signal experiences 20 dB attenuation. If input power is 1W, what is output power?
**Options:**
- a) 0.01 W
- b) 0.1 W
- c) 0.5 W
- d) 0.8 W

**Answer:** a) 0.01 W

**Question Explanation (English):** This question tests understanding of power attenuation in decibels and how to calculate output power from input power and attenuation.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về suy hao công suất theo đơn vị decibel và cách tính công suất đầu ra từ công suất đầu vào và độ suy hao.

**Answer Explanation (English):** 20 dB attenuation = 10^(20/10) = 100 times reduction. Output power = Input power / 100 = 1W / 100 = 0.01 W. Attenuation reduces power by the factor calculated from dB.

**Giải thích đáp án (Tiếng Việt):** Suy hao 20 dB = 10^(20/10) = giảm 100 lần. Công suất đầu ra = Công suất đầu vào / 100 = 1W / 100 = 0.01 W. Suy hao làm giảm công suất theo hệ số được tính từ dB.

---

### Q4. Cascaded Gain Calculation
**Question:** Three amplifiers with gains 10 dB, 15 dB, and 20 dB are cascaded. Total gain is:
**Options:**
- a) 35 dB
- b) 40 dB
- c) 45 dB
- d) 50 dB

**Answer:** c) 45 dB

**Question Explanation (English):** This question tests understanding of cascaded amplifier gain calculation where total gain is the sum of individual gains in dB.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về tính toán độ lợi của các bộ khuếch đại mắc nối tiếp, trong đó tổng độ lợi là tổng của các độ lợi riêng lẻ theo đơn vị dB.

**Answer Explanation (English):** Total gain = 10 dB + 15 dB + 20 dB = 45 dB. When amplifiers are cascaded, their gains in dB add together because dB is a logarithmic scale.

**Giải thích đáp án (Tiếng Việt):** Tổng độ lợi = 10 dB + 15 dB + 20 dB = 45 dB. Khi các bộ khuếch đại mắc nối tiếp, độ lợi của chúng cộng lại theo đơn vị dB vì dB là thang đo logarit.

---

### Q5. Resolution Bandwidth (RBW)
**Question:** What does RBW primarily affect in a spectrum analyzer?
**Options:**
- a) Dynamic range
- b) Frequency resolution
- c) Amplitude accuracy
- d) Sweep speed

**Answer:** b) Frequency resolution

**Question Explanation (English):** This question tests understanding of Resolution Bandwidth (RBW) parameter in spectrum analysis and its primary function.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về tham số RBW (Resolution Bandwidth) trong phân tích phổ và chức năng chính của nó.

**Answer Explanation (English):** RBW determines the frequency resolution of the spectrum analyzer. Smaller RBW provides better frequency resolution but slower sweep time. It's the bandwidth of the IF filter that determines how close two signals can be and still be resolved.

**Giải thích đáp án (Tiếng Việt):** RBW xác định độ phân giải tần số của máy phân tích phổ. RBW nhỏ hơn cung cấp độ phân giải tần số tốt hơn nhưng thời gian quét chậm hơn. Đây là băng thông của bộ lọc IF xác định hai tín hiệu có thể gần nhau đến mức nào và vẫn được phân giải.

---

### Q6. Video Bandwidth (VBW)
**Question:** VBW in spectrum analysis affects:
**Options:**
- a) Frequency resolution
- b) Noise floor visibility
- c) Sweep time
- d) Frequency span

**Answer:** b) Noise floor visibility

**Question Explanation (English):** This question tests understanding of Video Bandwidth (VBW) parameter and its effect on spectrum analyzer display.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về tham số VBW (Video Bandwidth) và ảnh hưởng của nó đến màn hình hiển thị của máy phân tích phổ.

**Answer Explanation (English):** VBW is the bandwidth of the video filter that smooths the display. Lower VBW reduces noise floor visibility and provides smoother traces, while higher VBW shows more noise but faster response to signal changes.

**Giải thích đáp án (Tiếng Việt):** VBW là băng thông của bộ lọc video làm mượt màn hình hiển thị. VBW thấp hơn giảm khả năng hiển thị mức nhiễu và cung cấp đường vẽ mượt mà hơn, trong khi VBW cao hơn hiển thị nhiều nhiễu hơn nhưng phản ứng nhanh hơn với thay đổi tín hiệu.

---

### Q7. Dynamic Range
**Question:** Dynamic range of a spectrum analyzer is the difference between:
**Options:**
- a) Maximum and minimum frequencies
- b) Maximum input and noise floor
- c) Maximum and minimum amplitudes
- d) Maximum and minimum power levels

**Answer:** b) Maximum input and noise floor

**Question Explanation (English):** This question tests understanding of dynamic range definition in spectrum analysis context.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về định nghĩa dải động trong ngữ cảnh phân tích phổ.

**Answer Explanation (English):** Dynamic range is the ratio between the largest and smallest signals that can be measured simultaneously. It's typically defined as the difference between the maximum input level (before distortion) and the noise floor, measured in dB.

**Giải thích đáp án (Tiếng Việt):** Dải động là tỷ số giữa tín hiệu lớn nhất và nhỏ nhất có thể đo đồng thời. Nó thường được định nghĩa là sự khác biệt giữa mức đầu vào tối đa (trước khi méo) và mức nhiễu, đo bằng dB.

---

### Q8. Signal Generator Accuracy
**Question:** Frequency accuracy of a signal generator is typically specified in:
**Options:**
- a) Hz
- b) ppm (parts per million)
- c) dB
- d) Percentage

**Answer:** b) ppm (parts per million)

**Question Explanation (English):** This question tests understanding of how frequency accuracy is specified for signal generators and test equipment.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về cách độ chính xác tần số được chỉ định cho máy phát tín hiệu và thiết bị đo.

**Answer Explanation (English):** Frequency accuracy is typically specified in ppm (parts per million) because it's a relative measure that scales with frequency. For example, 1 ppm accuracy at 1 GHz means ±1 kHz error, while at 10 GHz it means ±10 kHz error.

**Giải thích đáp án (Tiếng Việt):** Độ chính xác tần số thường được chỉ định bằng ppm (phần triệu) vì đây là phép đo tương đối có thể mở rộng theo tần số. Ví dụ, độ chính xác 1 ppm ở 1 GHz có nghĩa là sai số ±1 kHz, trong khi ở 10 GHz có nghĩa là sai số ±10 kHz.

---

### Q9. Modulation Accuracy
**Question:** EVM (Error Vector Magnitude) measures:
**Options:**
- a) Frequency stability
- b) Phase noise
- c) Modulation quality
- d) Power accuracy

**Answer:** c) Modulation quality

**Question Explanation (English):** This question tests understanding of EVM as a key parameter for measuring digital modulation quality.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về EVM như một tham số quan trọng để đo chất lượng điều chế số.

**Answer Explanation (English):** EVM measures the difference between the ideal constellation points and the actual received points, expressed as a percentage or dB. Lower EVM indicates better modulation quality and signal integrity.

**Giải thích đáp án (Tiếng Việt):** EVM đo sự khác biệt giữa các điểm chòm sao lý tưởng và các điểm thực tế nhận được, được biểu thị bằng phần trăm hoặc dB. EVM thấp hơn cho thấy chất lượng điều chế và tính toàn vẹn tín hiệu tốt hơn.

---

### Q10. Phase Noise
**Question:** Phase noise is typically measured in:
**Options:**
- a) dBc/Hz
- b) dBm/Hz
- c) dB/Hz
- d) dBc

**Answer:** a) dBc/Hz

**Question Explanation (English):** This question tests understanding of phase noise measurement units and their meaning.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về đơn vị đo nhiễu pha và ý nghĩa của chúng.

**Answer Explanation (English):** Phase noise is measured in dBc/Hz, where dBc means "dB relative to carrier" and /Hz indicates power spectral density. This unit shows the noise power in a 1 Hz bandwidth relative to the carrier power.

**Giải thích đáp án (Tiếng Việt):** Nhiễu pha được đo bằng dBc/Hz, trong đó dBc có nghĩa là "dB so với sóng mang" và /Hz chỉ ra mật độ phổ công suất. Đơn vị này cho thấy công suất nhiễu trong băng thông 1 Hz so với công suất sóng mang.

---

### Q11. VSWR Definition
**Question:** VSWR of 1.0 indicates:
**Options:**
- a) Perfect mismatch
- b) Perfect match
- c) 50% reflection
- d) 100% reflection

**Answer:** b) Perfect match

**Question Explanation (English):** This question tests understanding of VSWR (Voltage Standing Wave Ratio) and its relationship to impedance matching.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về VSWR (Tỷ số sóng đứng điện áp) và mối quan hệ của nó với việc phối hợp trở kháng.

**Answer Explanation (English):** VSWR = 1.0 indicates perfect impedance match (no reflection). VSWR = (1 + |Γ|)/(1 - |Γ|) where Γ is reflection coefficient. When Γ = 0 (perfect match), VSWR = 1.

**Giải thích đáp án (Tiếng Việt):** VSWR = 1.0 cho thấy phối hợp trở kháng hoàn hảo (không có phản xạ). VSWR = (1 + |Γ|)/(1 - |Γ|) trong đó Γ là hệ số phản xạ. Khi Γ = 0 (phối hợp hoàn hảo), VSWR = 1.

---

### Q12. Impedance Matching
**Question:** Maximum power transfer occurs when:
**Options:**
- a) Source impedance equals load impedance
- b) Source impedance is half load impedance
- c) Source impedance is twice load impedance
- d) Source impedance is zero

**Answer:** a) Source impedance equals load impedance

**Question Explanation (English):** This question tests understanding of the maximum power transfer theorem in RF circuits.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về định lý truyền công suất tối đa trong mạch RF.

**Answer Explanation (English):** Maximum power transfer occurs when source impedance equals load impedance (conjugate match for complex impedances). This minimizes reflection and maximizes power delivery to the load.

**Giải thích đáp án (Tiếng Việt):** Truyền công suất tối đa xảy ra khi trở kháng nguồn bằng trở kháng tải (phối hợp liên hợp cho trở kháng phức). Điều này giảm thiểu phản xạ và tối đa hóa công suất truyền đến tải.

---

### Q13. Return Loss
**Question:** Return loss of -20 dB means:
**Options:**
- a) 20% power reflected
- b) 1% power reflected
- c) 10% power reflected
- d) 5% power reflected

**Answer:** b) 1% power reflected

**Question Explanation (English):** This question tests understanding of return loss and its relationship to reflected power.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về suy hao phản xạ và mối quan hệ của nó với công suất phản xạ.

**Answer Explanation (English):** Return loss = -20 log₁₀(|Γ|) where Γ is reflection coefficient. -20 dB = -20 log₁₀(|Γ|), so |Γ| = 10^(-20/20) = 10^(-1) = 0.1. Reflected power = |Γ|² = 0.01 = 1%.

**Giải thích đáp án (Tiếng Việt):** Suy hao phản xạ = -20 log₁₀(|Γ|) trong đó Γ là hệ số phản xạ. -20 dB = -20 log₁₀(|Γ|), vậy |Γ| = 10^(-20/20) = 10^(-1) = 0.1. Công suất phản xạ = |Γ|² = 0.01 = 1%.

---

### Q14. Signal-to-Noise Ratio
**Question:** SNR of 20 dB means signal power is:
**Options:**
- a) 20 times noise power
- b) 100 times noise power
- c) 200 times noise power
- d) 1000 times noise power

**Answer:** b) 100 times noise power

**Question Explanation (English):** This question tests understanding of SNR calculation and its relationship to power ratios.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về tính toán SNR và mối quan hệ của nó với tỷ số công suất.

**Answer Explanation (English):** SNR = 10 log₁₀(Psignal/Pnoise). 20 dB = 10 log₁₀(Psignal/Pnoise), so Psignal/Pnoise = 10^(20/10) = 10² = 100. The signal power is 100 times the noise power.

**Giải thích đáp án (Tiếng Việt):** SNR = 10 log₁₀(Psignal/Pnoise). 20 dB = 10 log₁₀(Psignal/Pnoise), vậy Psignal/Pnoise = 10^(20/10) = 10² = 100. Công suất tín hiệu gấp 100 lần công suất nhiễu.

---

### Q15. Noise Figure
**Question:** Noise figure of 3 dB means:
**Options:**
- a) Output SNR is 3 dB worse than input SNR
- b) Output SNR is 3 dB better than input SNR
- c) Output power is 3 dB higher than input power
- d) Output power is 3 dB lower than input power

**Answer:** a) Output SNR is 3 dB worse than input SNR

**Question Explanation (English):** This question tests understanding of noise figure definition and its impact on system performance.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về định nghĩa hệ số nhiễu và ảnh hưởng của nó đến hiệu suất hệ thống.

**Answer Explanation (English):** Noise figure = 10 log₁₀(F) where F is noise factor. F = (SNRin)/(SNRout). 3 dB noise figure means F = 2, so output SNR is half (3 dB worse) than input SNR.

**Giải thích đáp án (Tiếng Việt):** Hệ số nhiễu = 10 log₁₀(F) trong đó F là hệ số nhiễu. F = (SNRin)/(SNRout). Hệ số nhiễu 3 dB có nghĩa là F = 2, vậy SNR đầu ra bằng một nửa (kém hơn 3 dB) so với SNR đầu vào.

---

### Q16. Thermal Noise Power
**Question:** Thermal noise power depends on:
**Options:**
- a) Temperature and bandwidth only
- b) Temperature, bandwidth, and resistance
- c) Temperature and resistance only
- d) Bandwidth and resistance only

**Answer:** a) Temperature and bandwidth only

**Question Explanation (English):** This question tests understanding of thermal noise power formula and its dependencies.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về công thức công suất nhiễu nhiệt và các yếu tố phụ thuộc.

**Answer Explanation (English):** Thermal noise power = kTB where k is Boltzmann's constant, T is temperature in Kelvin, and B is bandwidth. It's independent of resistance and depends only on temperature and bandwidth.

**Giải thích đáp án (Tiếng Việt):** Công suất nhiễu nhiệt = kTB trong đó k là hằng số Boltzmann, T là nhiệt độ tính bằng Kelvin, và B là băng thông. Nó không phụ thuộc vào điện trở và chỉ phụ thuộc vào nhiệt độ và băng thông.

---

### Q17. 1-dB Compression Point
**Question:** P1dB is the point where:
**Options:**
- a) Gain drops by 1 dB from linear
- b) Power output is 1 dB below maximum
- c) Input power is 1 dB below maximum
- d) Efficiency drops by 1 dB

**Answer:** a) Gain drops by 1 dB from linear

**Question Explanation (English):** This question tests understanding of the 1-dB compression point definition and its significance in amplifier characterization.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về định nghĩa điểm nén 1-dB và ý nghĩa của nó trong đặc trưng bộ khuếch đại.

**Answer Explanation (English):** P1dB is the input power level where the actual gain is 1 dB below the small-signal (linear) gain. This indicates the onset of gain compression and nonlinear behavior.

**Giải thích đáp án (Tiếng Việt):** P1dB là mức công suất đầu vào tại đó độ lợi thực tế thấp hơn 1 dB so với độ lợi tín hiệu nhỏ (tuyến tính). Điều này cho thấy sự bắt đầu của nén độ lợi và hành vi phi tuyến.

---

### Q18. Third-Order Intercept (IP3)
**Question:** IP3 is used to characterize:
**Options:**
- a) Gain compression
- b) Intermodulation distortion
- c) Phase noise
- d) Frequency stability

**Answer:** b) Intermodulation distortion

**Question Explanation (English):** This question tests understanding of IP3 as a key parameter for characterizing nonlinear distortion in RF systems.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về IP3 như một tham số quan trọng để đặc trưng méo phi tuyến trong hệ thống RF.

**Answer Explanation (English):** IP3 (Third-Order Intercept Point) characterizes intermodulation distortion. It's the theoretical point where third-order intermodulation products equal the fundamental signal power, indicating the system's linearity limit.

**Giải thích đáp án (Tiếng Việt):** IP3 (Điểm chặn bậc ba) đặc trưng cho méo điều chế tương hỗ. Đây là điểm lý thuyết tại đó các sản phẩm điều chế tương hỗ bậc ba bằng công suất tín hiệu cơ bản, cho thấy giới hạn tuyến tính của hệ thống.

---

### Q19. Filter Bandwidth
**Question:** 3-dB bandwidth is the frequency range where:
**Options:**
- a) Power drops to 50% of maximum
- b) Power drops to 70.7% of maximum
- c) Power drops to 90% of maximum
- d) Power drops to 99% of maximum

**Answer:** b) Power drops to 70.7% of maximum

**Question Explanation (English):** This question tests understanding of 3-dB bandwidth definition and its relationship to power transfer.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về định nghĩa băng thông 3-dB và mối quan hệ của nó với truyền công suất.

**Answer Explanation (English):** 3-dB bandwidth is where power drops to 70.7% of maximum (or -3 dB). This corresponds to voltage dropping to 70.7% because power ∝ voltage², and 20 log₁₀(0.707) = -3 dB.

**Giải thích đáp án (Tiếng Việt):** Băng thông 3-dB là nơi công suất giảm xuống 70.7% so với tối đa (hoặc -3 dB). Điều này tương ứng với điện áp giảm xuống 70.7% vì công suất ∝ điện áp², và 20 log₁₀(0.707) = -3 dB.

---

### Q20. Insertion Loss
**Question:** Insertion loss of a filter is:
**Options:**
- a) Loss in passband only
- b) Loss in stopband only
- c) Loss at center frequency
- d) Loss in both passband and stopband

**Answer:** d) Loss in both passband and stopband

**Question Explanation (English):** This question tests understanding of insertion loss definition and where it occurs in filter characteristics.

**Giải thích câu hỏi (Tiếng Việt):** Câu hỏi kiểm tra hiểu biết về định nghĩa suy hao chèn và nơi nó xảy ra trong đặc tính bộ lọc.

**Answer Explanation (English):** Insertion loss is the power loss when a filter is inserted into a transmission line. It occurs in both passband and stopband, though typically higher in stopband. It's measured as the ratio of power delivered to load with and without the filter.

**Giải thích đáp án (Tiếng Việt):** Suy hao chèn là mất mát công suất khi một bộ lọc được chèn vào đường truyền. Nó xảy ra ở cả dải thông và dải chặn, mặc dù thường cao hơn ở dải chặn. Nó được đo bằng tỷ số công suất cung cấp cho tải có và không có bộ lọc.

---

*This document provides detailed answers and explanations for Part I (Q1-Q20) of the RF & Wireless Interview Test, covering RF Fundamentals & Measurement concepts.* 